# Unity-PixelPerfectPolygonCollider2D
I found that when built, I encountered some errors. So, when building I wanted to exclude this file from being built.

I added two lines;

#if UNITY_EDITOR
And
#endif

before and after the first and last function.

This excludes the code from being built which resolves any errors when building.
The code still works in the editor which is exactly what we want.
