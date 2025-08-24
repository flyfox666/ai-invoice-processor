# FlexiVoice (Smart AI Invoice Parser)

[English](./README.md) | [中文](./README.zh-CN.md)

FlexiVoice is an intelligent invoice processing tool designed specifically for **finance and administrative personnel without a technical background**. It completely revolutionizes the tedious traditional process of manual data entry, making advanced AI technology accessible to everyone.

The most significant feature of this application is its **extremely lightweight, pure front-end architecture**. Users do not need to install any software or rely on a back-end server. All data processing and AI calls are securely completed within the user's local browser, ensuring data privacy and providing an "out-of-the-box" user experience. At its core is a powerful **multi-modal large language model** that can "read" and understand various invoices just like a human. Whether it's a standard electronic PDF or a scanned image of an invoice from a phone, the system can achieve high-precision extraction of key information.

### How to Use

This is a pure front-end application and is extremely easy to use.

1.  **Download the Code**: Clone or download this repository to your local machine.
2.  **Open the File**: Simply open the `FlexiVoice-智能AI发票识别器.html` file directly in a modern web browser like Chrome, Firefox, or Edge.
3.  **Step 1: Configure AI Model**
    * **API Provider**: The application has pre-configured settings for several mainstream AI providers (e.g., VolcEngine, Zhipu AI). You can select one from the dropdown list.
    * **API Key**: Enter your personal API key from the chosen provider. Your key is only used in your browser and is never stored or sent anywhere else.
    * **Text & Vision Models**: Select the appropriate text and vision models. The list will update based on the provider you choose.
    * **Custom Models**: If your provider is not listed, simply select **"Other"**. This will allow you to enter a custom API Base URL and the specific model names you wish to use.
4.  **Step 2: Upload Invoices**
    * Click the upload area or drag and drop your invoice files (PDF, PNG, JPG). You can upload multiple files at once.
5.  **Step 3: Start Processing**
    * Click the "🚀 Start Smart Recognition" button to begin.
    * For scanned PDFs or complex invoices, you can check the "Force vision model for all PDFs" option for higher accuracy (this may increase costs).
    * The results will appear in the table below, and you can export them to a CSV file when finished.

### Core Features

1.  **Pure Front-end, Zero Technical Barrier**: The interface is extremely simple and tailored to the operational habits of financial staff. All functions can be completed within the browser without any IT support, making it truly ready to use out of the box.
2.  **Powerful AI Multi-modal Recognition**: It utilizes an advanced vision-language model that can not only process text but also accurately recognize image content, easily handling complex and irregular invoice formats with an accuracy far exceeding traditional OCR.
3.  **Intelligent Cost Optimization Engine**: The system automatically determines the invoice type and prioritizes using more cost-effective text models for processing. It only calls upon advanced vision models when necessary, saving every penny on API call costs for the user while ensuring high accuracy.
4.  **Flexible Model Selection & Data Export**: Users can freely choose models from different AI service providers and export the structured, recognized data into a CSV table with a single click, seamlessly integrating into existing financial workflows.

### Value Proposition

For the majority of finance and administrative staff, invoice processing has always been a repetitive, time-consuming, and error-prone task. Traditional solutions are either too expensive and complex or have limited recognition capabilities. FlexiVoice aims to provide a perfect, **"accessible-to-all"** solution for this common pain point using cutting-edge AI technology.

#### Core Value:

1.  **Democratizing Technology, Empowering Frontline Staff**: We believe that the most powerful technology should serve those who need it most. FlexiVoice packages top-tier multi-modal AI capabilities into an incredibly simple web tool. It empowers every finance professional to become a data processing expert, using AI as a powerful assistant to boost personal productivity.
2.  **Goodbye to Tedium, Hello to Ultimate Efficiency**: Through one-click batch processing, the system can complete in minutes what used to take hours of manual data entry. This not only frees employees from tedious tasks but also allows them to focus on more valuable business activities like financial auditing and cost analysis.
3.  **Extremely Lightweight with Zero-Cost Deployment**: Thanks to its **pure front-end implementation**, this application does not rely on any back-end servers. Enterprises do not need to bear any deployment or maintenance costs. This "zero-burden," lightweight model is especially suitable for small and medium-sized enterprises and teams looking for a quick, low-cost digital upgrade.
4.  **Future-Proof Adaptability**: The use of multi-modal models ensures that the system can not only handle today's invoices but also easily adapt to various new types of bills and receipts in the future. The open model interface also guarantees that the system can continuously integrate more efficient and economical AI brains, ensuring it never becomes obsolete.


