# 🚀 Employee Onboarding Automation using RPA  

## 📌 Project Overview  
This project automates the **employee onboarding process** using **Robotic Process Automation (RPA) with UiPath**. Traditional onboarding is time-consuming, prone to errors, and requires extensive manual effort. This automation streamlines key processes such as:  

- **Automating interview call scheduling**  
- **Generating personalized offer letters**  
- **Creating employee ID cards**  

By leveraging **UiPath**, this project enhances efficiency, minimizes errors, and improves HR productivity.  

---

## 🎯 Objectives  
- 📄 Automate **document verification, data extraction, and entry**.  
- 📧 Enable automatic **interview call scheduling**.  
- 📝 **Generate offer letters dynamically** based on predefined templates.  
- 🆔 Create **employee ID cards** with branding and security features.  
- 🔄 Reduce manual workload and improve **HR efficiency**.  

---

## ⚙️ Technologies Used  
- **UiPath** – For RPA automation.  
- **OCR & Data Extraction** – For processing employee details.  
- **Email Automation** – For interview calls & offer letters.  
- **Document Templates** – For ID card and offer letter generation.  

---

## 📂 Project Structure  
Employee-Onboarding-RPA/
│── XAML_Files/                  # UiPath workflows (XAML files)
│   ├── InterviewCall.xaml        # Automates interview call scheduling
│   ├── OfferLetter.xaml          # Generates offer letters dynamically
│   ├── IDCardGeneration.xaml     # Automates employee ID card creation
│   ├── Main.xaml                 # Orchestrator for the onboarding process
│
│── Templates/                    # Predefined templates for documents
│   ├── Offer_Letter_Template.docx
│   ├── ID_Card_Template.png
│
│── Dependencies/                  # Any external dependencies (if applicable)
│
│── README.md                      # Project documentation

🔧 Dependencies & Setup

To run this project, install the following dependencies in UiPath Studio:

✅ UiPath Packages (Install via Manage Packages)

UiPath.Excel.Activities → For handling Excel data (e.g., reading employee details).

UiPath.Mail.Activities → For sending emails (interview call scheduling & offer letter dispatch).

UiPath.Word.Activities → For generating offer letters from Word templates.

UiPath.PDF.Activities → If offer letters need to be converted to PDFs.

UiPath.DocumentUnderstanding → If OCR is used for document verification.

UiPath.Forms.Activities → For UI-based user input (if applicable).

UiPath.UIAutomation.Activities → For interacting with web-based HR portals.

📌 External Dependencies

Microsoft Word (or equivalent) → For offer letter template processing.

SMTP or Outlook Email Account → For email automation.

Google Drive/OneDrive API (Optional) → If documents are uploaded to cloud storage.
🛠 Installation Steps

Open UiPath Studio.

Navigate to Manage Packages (📦 icon in the ribbon).

Search for the required package (e.g., UiPath.Excel.Activities).

Click Install → Save → Restart UiPath Studio.

🎬 How to Use

Running the UiPath XAML Files

1.Clone the Repository
git clone https://github.com/yourusername/Employee-Onboarding-RPA.git
cd Employee-Onboarding-RPA

2.Open UiPath Studio and load the Main.xaml file.

3.Ensure dependencies are installed (see above).

4.Run the automation by executing Main.xaml.

📽️ Project Demo 
- [📽️ Interview Call Automation](https://github.com/your-username/your-repo/releases/download/v1.0.0-employee-onboarding/interview-call.mp4)
- [📽️ Offer Letter Generation](https://github.com/your-username/your-repo/releases/download/v1.0.0-employee-onboarding/offer-letter.mp4)
- [📽️ ID Card Creation](https://github.com/your-username/your-repo/releases/download/v1.0.0-employee-onboarding/id-card.mp4)
🤝 Contribution

Feel free to contribute by raising issues or submitting pull requests!

📜 License

This project is licensed under MIT License. You are free to use and modify it as needed.

