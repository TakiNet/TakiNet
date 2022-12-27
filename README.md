Перед main:
local image
В main
image = imgui.CreateTextureFromFile("moonloader/image.png")
В рендере
imgui.Image(image, imgui.ImVec2(imgui.GetWindowWidht(), imgui.GetWindowHeight()/2))
