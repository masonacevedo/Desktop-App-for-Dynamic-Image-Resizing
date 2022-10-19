# Seam_Carving_Desktop_App

The goal for this project 
is a simple application that prompts
a user to upload an image, and enables them to 
perform *content-aware* image resizing using 
seam-carving. What exactly does that mean? 

Well, it enables you to change the dimensions of an
image in a way that keeps the important stuff in the frame
as-is, and gets rid of un-important background
stuff, in a way that *does not* result in squished,
stretched, or out-of-proportion pictures. For example, consider
the following image:



<img src = "https://user-images.githubusercontent.com/48235053/196591446-25fb8d5f-d1a8-4bf5-a3ad-01098db55c79.jpg" width = "800" height = "600">

If we wanted to reduce the height, it would be nice if the computer could recognize that we should just 
get rid of all that empty sky, and preserve the dimensions/proportions of the building, beach, and people in
the foreground. That's exactly what seam-carving does:



<img src = "https://user-images.githubusercontent.com/48235053/196592680-8b57fd3c-6350-4513-98a1-8ce66eb4dcec.jpg" width = "800" height = "440">


To learn about this approach, watch this 
4 minute youtube video:
[https://www.youtube.com/watch?v=6NcIJXTlugc&]( https://www.youtube.com/watch?v=6NcIJXTlugc ) 
