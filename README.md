# Ubuntu Style for ImGui

## Color palette
This is the color palette used in this project
![Palette](https://raw.githubusercontent.com/mariomamede/imgui-ubuntu-style/main/ubuntu%20color%20palette.jpg)

## Preview
![Preview](https://raw.githubusercontent.com/mariomamede/imgui-ubuntu-style/main/imgui%20ubuntu%20style%20preview.webp)

## Code
### Border and Rounding
```
//Borders
ImGui::GetStyle().WindowBorderSize = 0.0f;
ImGui::GetStyle().FrameBorderSize = 0.0f;
ImGui::GetStyle().PopupBorderSize = 0.0f;

//Rounding
ImGui::GetStyle().WindowRounding = 0.0f;
ImGui::GetStyle().ChildRounding = 0.0f;
ImGui::GetStyle().FrameRounding = 0.0f;
ImGui::GetStyle().PopupRounding = 0.0f;
ImGui::GetStyle().ScrollbarRounding = 0.0f;
ImGui::GetStyle().GrabRounding = 0.0f;
ImGui::GetStyle().LogSliderDeadzone = 0.0f;
ImGui::GetStyle().TabRounding = 0.0f;
```

### Colors
```
ImVec4* colors = ImGui::GetStyle().Colors;
colors[ImGuiCol_Text]                   = ImVec4(1.00f, 1.00f, 1.00f, 1.00f);
colors[ImGuiCol_TextDisabled]           = ImVec4(0.40f, 0.40f, 0.40f, 1.00f);
colors[ImGuiCol_WindowBg]               = ImVec4(0.07f, 0.07f, 0.07f, 1.00f);
colors[ImGuiCol_ChildBg]                = ImVec4(0.07f, 0.07f, 0.07f, 1.00f);
colors[ImGuiCol_PopupBg]                = ImVec4(0.07f, 0.07f, 0.07f, 1.00f);
colors[ImGuiCol_Border]                 = ImVec4(1.00f, 1.00f, 1.00f, 1.00f);
colors[ImGuiCol_BorderShadow]           = ImVec4(0.00f, 0.00f, 0.00f, 0.00f);
colors[ImGuiCol_FrameBg]                = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_FrameBgHovered]         = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_FrameBgActive]          = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_TitleBg]                = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_TitleBgActive]          = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_TitleBgCollapsed]       = ImVec4(0.00f, 0.00f, 0.00f, 0.51f);
colors[ImGuiCol_MenuBarBg]              = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ScrollbarBg]            = ImVec4(0.02f, 0.02f, 0.02f, 0.53f);
colors[ImGuiCol_ScrollbarGrab]          = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ScrollbarGrabHovered]   = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ScrollbarGrabActive]    = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_CheckMark]              = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_SliderGrab]             = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_SliderGrabActive]       = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_Button]                 = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ButtonHovered]          = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_ButtonActive]           = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_Header]                 = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_HeaderHovered]          = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_HeaderActive]           = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_Separator]              = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_SeparatorHovered]       = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_SeparatorActive]        = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ResizeGrip]             = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_ResizeGripHovered]      = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_ResizeGripActive]       = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_Tab]                    = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_TabHovered]             = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_TabActive]              = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_TabUnfocused]           = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_TabUnfocusedActive]     = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_PlotLines]              = ImVec4(1.00f, 1.00f, 1.00f, 1.00f);
colors[ImGuiCol_PlotLinesHovered]       = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_PlotHistogram]          = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_PlotHistogramHovered]   = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_TableHeaderBg]          = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_TableBorderStrong]      = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_TableBorderLight]       = ImVec4(0.20f, 0.20f, 0.20f, 1.00f);
colors[ImGuiCol_TableRowBg]             = ImVec4(0.07f, 0.07f, 0.07f, 1.00f);
colors[ImGuiCol_TableRowBgAlt]          = ImVec4(1.00f, 1.00f, 1.00f, 0.06f);
colors[ImGuiCol_TextSelectedBg]         = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_DragDropTarget]         = ImVec4(0.91f, 0.33f, 0.13f, 1.00f);
colors[ImGuiCol_NavHighlight]           = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_NavWindowingHighlight]  = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_NavWindowingDimBg]      = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
colors[ImGuiCol_ModalWindowDimBg]       = ImVec4(0.05f, 0.52f, 0.13f, 1.00f);
```
