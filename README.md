<p align="center"><a href="https://www.sawitpro.com/" target="_blank"><img src="https://static.wixstatic.com/media/759737_bb3e5ad0e411479782bdaca6f4fa3bda~mv2.png/v1/fill/w_80,h_80,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/SawitPro%20Logo.png" width="400" alt="SawitPRO Logo"></a></p>



## Secure Image Uploading Web Application

This GitHub repository hosts a web application developed as a technical assignment for the Cybersecurity Engineer position at Sawit Pro. The application allows users to securely upload and store image files while ensuring the confidentiality and integrity of the data. Below are the key features and functionalities of the application:

Features:
- User Registration & Login: Users can register for an account and securely log in using their credentials. All user credentials are handled securely to prevent unauthorized access.   
- Secure Image Upload: Robust security mechanisms are implemented to validate and safely upload image files. The application prevents the upload of potentially malicious or oversized files by implementing strict validation checks.
- Image Storage: Uploaded images are stored securely and confidentially. Encryption techniques are employed to safeguard the images, ensuring that they remain protected even in the event of a security breach.
- Image Retrieval: Each user has a personalized gallery space where they can view their uploaded images. The application provides a user-friendly interface for easy navigation and browsing of images.
- This GitHub repository hosts a web application developed as a technical assignment for the Cybersecurity Engineer position at Sawit Pro. The application allows users to securely upload and store image files while ensuring the confidentiality and integrity of the data. 
- Image Deletion: Users are given the option to delete their uploaded images. This feature adds flexibility and control to the user experience, allowing them to manage their uploaded content as needed.
- User Feedback: The application is interactive and provides feedback to users upon successful operations or potential errors. This enhances the user experience by keeping users informed about the status of their actions.

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Summary
- User Authentication and Security:
    - Utilizes Laravel Jetstream's built-in features for secure user authentication.
    - Implements password hashing, session management, and CSRF protection to safeguard user credentials and prevent unauthorized access.
- File Upload Security Measures:
    - Implements strict validation rules to ensure only permitted file types (e.g., .jpg, .png) are uploaded.
    - Sets a maximum file size limit and utilizes ClamAV for scanning uploads, mitigating risks associated with malicious or oversized files.
- Confidential Image Storage:
    - Leverages Laravel's file storage system, ensuring secure storage of uploaded images.
    - Encourages encryption techniques for additional security, although defaults to Laravel's reliable storage mechanisms for efficient handling.
- User Interaction and Management:
    - Provides users with personalized gallery spaces for convenient image viewing.
    - Empowers users to manage their uploaded images by offering options for deletion or modification.
- Interactive Feedback Mechanisms:
    - Offers real-time feedback to users upon successful operations or errors, enhancing user experience and engagement.
    - Keeps users informed about the status of their actions, promoting transparency and usability.
