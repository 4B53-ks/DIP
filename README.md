# My Digital Image Processing (DIP) Project

This is my learning project where I'm learning how to work with images using Python. The folder has two main parts:
1. A bunch of learning experiments to understand how image processing works
2. A cool document scanner app that I built to put everything together

---

## What's Inside

Here's what the folder looks like:

```
dip_proj/
├── requirements.txt          # List of packages I need to install
├── dip_learn/               # My learning experiments (10 of them)
│   ├── ml_model.ipynb       # Trying out machine learning stuff
│   ├── Expt 1/              # First experiment - learning colors
│   ├── expt2/               # Second experiment
│   ├── expt3 to expt10/     # More experiments
│   └── Images/              # The test images I use
└── dip_final_proj/          # My final project - document scanner
    └── dio_proj.ipynb       # The actual scanner code
```

---

## Learning Phase (in the `dip_learn/` folder)

I made 10 experiments to learn image processing step by step.

### What each experiment does:

- **Experiment 1**: Understanding colors
  - Learning how colors work (BGR, RGB, Grayscale, HSV)
  - Changing image colors
  - Showing images on screen

- **Experiments 2-10**: More image tricks
  - Finding edges in images
  - Blurring images
  - Making images brighter or darker
  - And lots more cool stuff!

---

## My Cool Project: Document Scanner

This is my final project - it scans documents from images! Here's what it does:

### Step by step:

1. **Finds the document** - Looks for the edges and detects where the document is
2. **Fixes the angle** - If the document is tilted, it straightens it out
3. **Makes it clearer** - Converts to black and white to make it look like a real scan
4. **Shows the result** - Displays the before and after side by side

### The functions I wrote:

- `order_points()` - Organizes the corners of the document
- `four_point_transform()` - Fixes the angle/perspective
- `scan_document()` - Does the whole scanning process

---

## Getting Started

### What you need:

- Python 3.7 or newer
- pip (comes with Python)

### Installation

1. Go to the project folder in your terminal:

2. Setup your environment:
    for bash
    ```
    pyhton -m venv venv
    source venv/Scripts/activate
    ```

3. Install the packages:
   ```
   pip install -r requirements.txt
   ```

   This will install:
   - **numpy** - For doing math with numbers
   - **matplotlib** - For showing images and graphs
   - **opencv-python** - The main library for image stuff

---

## How to Run Things

### Running the Learning Experiments

1. **Open the experiment:**
   - Just open any experiment file in VS Code (like `dip_learn/Expt 1/expt1.ipynb`)
   - VS Code will show it as a notebook

2. **Run the code:**
   - Click the "Run" button next to each code block
   - Watch what happens!
   - You can change numbers and run again to see different results

### Running the Document Scanner

1. **Get an image:**
   - Take a photo of a document or use one you have
   - Put it in the `dip_final_proj/` folder
   - Remember the name (like `paper.jpg`)

2. **Open the notebook:**
   - Open `dip_final_proj/dio_proj.ipynb` in VS Code

3. **Change the image name:**
   - In the last code block, change `'paper.jpg'` to your image name

4. **Run it:**
   - Click the Run button
   - You'll see 3 images:
     - Your original photo with a green outline around the document
     - The document straightened out
     - The final black and white scan

---

## Packages I Use

```
numpy              - Math and numbers
matplotlib         - Showing images
opencv-python      - Image processing
```

Run `pip install -r requirements.txt` to get all of them

---

## Tips to Make It Work Better

### For Learning:
- Go through experiments in order (1, 2, 3... 10)
- Try changing the numbers in the code and see what happens
- Read the comments to understand what's going on

### For the Document Scanner:
- Use clear photos of documents
- Good lighting helps a lot!
- The background shouldn't be too busy or complicated
- Make sure the document takes up most of the photo
- If it doesn't find the document, try a different photo

---

## Important Stuff to Know

- Put your test images in the `Images/` folder inside each experiment
- When running notebooks, make sure you're in the right folder
- Some code blocks might take a few seconds to run - be patient!

---

## What I'm Learning

By going through all of this, I'm learning:

✅ How colors work in images  
✅ How to make images look different  
✅ How to find edges and shapes  
✅ How to build real projects with images  



---

## Things I Can Do

- Change numbers in the code to experiment
- Try with my own photos
- Add new experiments
- Make the scanner work better

---

## Get Started!

Start with Experiment 1 in `dip_learn/`, then try the others in order. When you feel ready, move on to the document scanner project!

Good luck! 🎉
