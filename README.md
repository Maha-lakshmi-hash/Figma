# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import React from "react";
import kimetsuNoYaiba1 from "./kimetsu-no-yaiba-1.png";

export const Image = () => {
  return (
    <div className="w-[2544px] h-[3191px]">
      <img
        className="fixed top-0 left-0 w-[2544px] h-[3191px] aspect-[0.8] object-cover"
        alt="Kimetsu no yaiba"
        src={kimetsuNoYaiba1}
      />
    </div>
  );
};
import React from "react";
import iWantToEatYourPancreas1 from "./i-want-to-eat-your-pancreas-1.png";

export const Image = () => {
  return (
    <div className="w-[2331px] h-[3447px]">
      <img
        className="fixed top-0 left-0 w-[2331px] h-[3447px] aspect-[0.68] object-cover"
        alt="I want to eat your"
        src={iWantToEatYourPancreas1}
      />
    </div>
  );
};
import React from "react";
import kny1 from "./kny-1.png";

export const Image = () => {
  return (
    <div className="w-[2258px] h-[3360px]">
      <img
        className="fixed top-0 left-0 w-[2258px] h-[3360px] aspect-[0.67] object-cover"
        alt="Kny"
        src={kny1}
      />
    </div>
  );
};
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 143145.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
