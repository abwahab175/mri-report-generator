# MRI Report Generator with Google Gemini and PDF Export

This project is a Streamlit-based web application that generates MRI brain reports using a YOLOv8 model for image segmentation and Google Gemini for AI-powered report generation. The application allows users to upload MRI images, segment them to identify tumors, and generate a detailed PDF report with the segmented image.

## Features

- Upload MRI Images: Users can upload MRI images with mask overlays for processing.
- YOLOv8 Segmentation: The application uses a YOLOv8 model to segment and detect regions of interest in the MRI images.
- Google Gemini Integration: The application integrates with Google Gemini to generate detailed MRI reports based on the detected regions.
- PDF Report Generation: The application creates a downloadable PDF report that includes the segmented MRI image and the AI-generated report.

## How It Works

1. Upload MRI Image: Users upload an MRI image (PNG, JPG, or JPEG) with mask overlay.
2. Image Segmentation: The YOLOv8 model processes the image to segment regions of interest, such as tumors.
3. AI Report Generation: Google Gemini generates a detailed report based on the segmented image and findings.
4. Download PDF Report: The application generates a PDF file with the segmented image and AI-generated report, which can be downloaded by the user.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:

```bash
Copy code
git clone https://github.com/abwahab175/mri-report-generator.git
cd mri-report-generator
```

2. Install the required dependencies:

```bash
Copy code
pip install -r requirements.txt
```

3. Run the Streamlit application:

```bash
Copy code
streamlit run app.py
```

## Usage

1. Launch the application by running the above command.
2. Upload an MRI image with a mask overlay using the file uploader.
3. Click the "Generate PDF Report" button to process the image and generate the report.
4. Download the generated PDF report.

## Dependencies

- Python 3.x
- Streamlit
- FPDF
- PIL (Pillow)
- YOLOv8
- Google Gemini API

## Contributing

Contributions are welcome! If you have suggestions, enhancements, or bug fixes, please follow the steps below:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

- Abdul Wahab - [abwahab175@gmail.com](mailto:abwahab175@gmail.com)
