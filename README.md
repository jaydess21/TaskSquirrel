# Task Squirrel

## Overview
Task Squirrel is an app designed to assist parents in motivating their children to complete chores and lend a helping hand. The app offers a list of tasks that users can assign to their children, and it requires users to attach photos as proof of task completion. Additionally, Task Squirrel provides a map feature to display the location where each photo was taken.

<div>
    <a href="https://www.loom.com/share/55328ff86d8148f497698dc08f9185b1">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/55328ff86d8148f497698dc08f9185b1-with-play.gif">
    </a>


## 🎯 Goals
By the end of this lab, you will be able to:

[x] Utilize PHPickerViewController to select photos and retrieve photo data from the photo library.

[x] Implement MapKit to display custom annotations on a map.

## Features
### Required Features
- View a list of tasks that need to be completed for the scavenger hunt.
- Each task is represented by a Task data model with the following properties:
  - Title
  - Description
  - Image (of type UIImage?)
  - isComplete (a computed property that returns true if an image is attached).
- The task list displays the title property of each task.
- Tapping on a task provides access to its details, including:
  - Title
  - Description
  - Completion status
  - An annotation on an MKMapView that contains the attached photo.
- If no photo is attached, the map view is hidden, and an "Attach Photo" button is displayed instead.
- The "Attach Photo" button is replaced by the map view once a user attaches a photo.
- Users can attach a photo within the task detail view, marking the task as completed in both the detail view and task list.
- Users can view the location of the attached photo on a map inside the task view.

## Getting Started
To get started with Task Squirrel, follow these steps:

1. Clone this repository to your local machine. 
2. Open the Xcode project in the repository.
3. Build and run the app on your iOS device or simulator.

## Dependencies
- [PHPickerViewController](https://developer.apple.com/documentation/phpickerviewcontroller)
- [MapKit](https://developer.apple.com/documentation/mapkit)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- This project was developed as part of Lab 4 for Code Path - IOS Mobile Apps

---

**Note:** Replace `[link_to_screenshot_image]`, `[your-username]`, `[Course Name]`, `[Your Institution]`, and any other placeholders with actual information relevant to your project.

