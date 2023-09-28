##Responsive-landing-page

### Header Section:

HTML Tags:
- `<div class="header md:flex justify-between items-center mx-5">`: This `<div>` represents the header section of the landing page.

Tailwind CSS Classes:
- **`header`**: A custom CSS class for styling the header section.
- **`md:flex justify-between items-center mx-5`**: These classes make the header section responsive. On mobile devices, it displays as a single column, while on larger devices, it appears as two columns with the logo on the left and the navigation menu on the right.

### Navigation Menu:

HTML Tags:
- `<div class="md:flex">`: This `<div>` contains the navigation menu items.

Tailwind CSS Classes:
- **`md:flex`**: Makes the navigation menu responsive. On mobile devices, it's hidden by default, and a hamburger menu icon is used to reveal it. On larger devices, it's displayed at all times.
- **`flex justify-center items-center gap-x-2 mt-2`**: Styles the navigation menu items, making them centered and spaced evenly.
- **`bg-green-600 w-8 h-8 rounded-3xl flex flex-col justify-center items-center`**: Creates a green square with a layer group icon inside it.
- **`font-medium font-sans`**: Sets the font weight to medium and uses a sans-serif font for the "Geekster" heading.
- **`md:border-l-2 border-gray-400 pl-4 ml-4 mr-auto`**: Adds a left border to the navigation menu items on larger devices.
- **`flex gap-x-4 justify-center items-center text-gray-400`**: Makes the navigation menu items spaced evenly and sets their text color to gray.
- **`text-base hover:text-gray-900`**: Changes the text color to gray-900 on hover for the navigation menu items.

  # Header for Desktop

  ![header section](https://github.com/shah9380/Responsive-landing-page/assets/130676464/50f8c70a-cf79-44fb-a75e-9cd6a3d86bcd)

  # Header for Mobile

  ![Header-Mobile](https://github.com/shah9380/Responsive-landing-page/assets/130676464/216d01fb-99a1-4eab-aeaa-b7eddb8cfdce)

### Main Section:

HTML Tags:
- `<div class="mt-4 px-5 py-24 md:flex gap-x-6">`: This `<div>` represents the main section of the landing page.

Tailwind CSS Classes:
- **`mt-4 px-5 py-24 md:flex gap-x-6`**: Adds margin, padding, and gap between elements in the main section. Also includes responsive adjustments for larger screens.
- **`text-center flex flex-col justify-center items-center pb-12 md:w-1/2`**: Styles the text block in the main section to be centered and take half the width on larger screens.
- **`text-4xl font-medium pb-4`**: Sets the heading size to text-4xl and font weight to medium.
- **`pb-8`**: Adds bottom padding to the heading.
- **`flex gap-x-3`**: Spaces the "Yes" and "No" buttons evenly.
- **`px-6 py-2 bg-green-500 hover:bg-indigo-600 rounded text-white`**: Styles the "Yes" button with a green background that turns indigo-600 on hover.
- **`px-6 py-2 bg-gray-100 hover:bg-gray-200 rounded`**: Styles the "No" button with a gray background that turns gray-200 on hover.

#Main for Desktop

![Main Section for Desktop](https://github.com/shah9380/Responsive-landing-page/assets/130676464/17c15fea-902a-435f-8184-7c61ad5a71b3)


#Main for Mobile
![Main-Mobile](https://github.com/shah9380/Responsive-landing-page/assets/130676464/819456dc-3633-4a40-b965-91f107c096e4)


### Image Section:

HTML Tags:
- `<div class="px-auto flex justify-center items-center md:grow pr-24 pb-24 pl-24">`: This `<div>` represents the image section of the landing page.

Tailwind CSS Classes:
- **`px-auto flex justify-center items-center md:grow pr-24 pb-24 pl-24`**: Centers and resizes the image on larger screens and adds padding.

![image1](https://github.com/shah9380/Responsive-landing-page/assets/130676464/3f61d87a-6d59-4694-b914-f432f98a8748)

These sections and their respective classes create the responsive and professional design of the landing page, ensuring it looks great on various devices.

[Feel free to Explore my WebPage](https://shah9380.github.io/Responsive-landing-page/)
