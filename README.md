<p align="center"><img src="logo.png" alt="MedSpot Logo" width="500"></p>

**MedSpot is a web-based platform designed to revolutionize how people in Bamenda, Cameroon, find and access medications.** It tackles the common problem of not knowing which pharmacies have the drugs you need, saving users valuable time and potentially improving health outcomes, especially in urgent situations.

**Here's a comprehensive breakdown:**

*   **Core Functionality:** MedSpot acts as a central hub connecting users directly to pharmacies, providing real-time information on drug availability.

*   **For Users (Built with React JS):**

    *   **Drug Search:** Users can easily search for medications using a user-friendly interface. They can search by brand name, generic name, or even local names that are commonly used in Bamenda.
    *   **Pharmacy Locator:** MedSpot displays a list of pharmacies carrying the searched drug, along with their location on a map (using Google Maps API or OpenStreetMap, potentially integrating local mapping services for better accuracy in Bamenda).
    *   **Directions:** Users can get directions to the chosen pharmacy directly from within the app, using either the in-app mapping or a redirect to Google Maps.
    *   **Pharmacy Details:** Access key information about each pharmacy, such as address, phone number, hours of operation, and potentially user reviews (to be implemented).
    *   **Favorites:** Users can save pharmacies to a "favorites" list for quick access in the future.
    *   **Language Support:** The user interface will support multiple languages including English, French, and Pidgin English to cater to the diverse population of Bamenda.

*   **For Pharmacies (Pharmacy Panel Built with Laravel):**

    *   **Registration & Profile:** Pharmacies can register and create a profile with essential details like address, contact information, and hours of operation.
    *   **Inventory Management:** Pharmacies can easily list and manage their drug inventory, including updating stock levels in real-time.
    *   **Drug Information:** Pharmacies can list drugs with their generic names, brand names, and common local names, ensuring accuracy in search results.
    *   **Location Setting:** Precise location settings using maps to enable potential customers find them

*   **Admin Panel (Built with Laravel):**

    *   **User Management:** Manage user accounts and permissions.
    *   **Pharmacy Management:** Manage pharmacy listings, verify pharmacy licenses, and ensure data integrity.
    *   **Content Management:** Manage website content, announcements, and updates.
    *   **Data Analysis:** Monitor system usage, identify trends, and generate reports to improve the platform.

*   **Key Features & Benefits:**

    *   **Improved Drug Accessibility:** Significantly reduces the time and effort required to find needed medications.
    *   **Real-time Information:** Provides up-to-date information on drug availability, minimizing unnecessary trips to pharmacies.
    *   **Localized:** Designed with the specific needs of the Bamenda community in mind, including language support and consideration for internet connectivity challenges (offline capabilities for saved information).
    *   **Enhanced Efficiency:** Streamlines the process of finding and obtaining medications, benefiting both patients and pharmacies.
    *   **Trust & Reliability:** Aims to build trust through verified pharmacy listings (admin ensures all pharmacies are licensed and legal) and user reviews (future implementation).
    *   **Data Security:** Implements encryption protocols to protect user and pharmacy data.

*   **No E-Commerce:** It's important to note that MedSpot is **not** an online pharmacy. No drug purchases or transactions are conducted directly on the platform. It's solely a locator service to help connect people with pharmacies that have the medications they need.

In short, MedSpot is a powerful tool for improving healthcare accessibility in Bamenda by making it easier for people to find the medications they need, when they need them. It is designed with local needs in mind to ensure the best possible user experience.


⭐ Special Thanks To:

ravindra135 - From GitHub - For Open Source Admin Dashboard
Creative Tim - For The Open Source Theme.
Leena Lavanya - From Codepen - For the Custom Error 403 Page.
Swarup Kumar Kuila - From Codepen - For the Custom Error 404 Page.
