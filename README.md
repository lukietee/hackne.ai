🏆 2024 HackCC 2nd Place Winner | hackne.ai - Where AI meets your AM/PM skincare routine

DevPost: https://devpost.com/software/hackne-io

By: Minh Truong, Lucas Trinh, Princeton Nguyen, and Aadhithiya Anbalagan

**Why hackne.ai?**

Acne is one of the most common skin conditions worldwide. In the United States, acne affects more than 50 million people every year. Acne can cause serious consequences, such as low self-esteem, social isolation, and even depression. Many of those who struggle with acne don't know, or don't have access to resources to treat it.

hackne.ai is a solution for those who are struggling with acne and don't have immediate access to a dermatologist. After completing a survey and scanning their face through an advanced acne diagnosis machine learning model, hackne.ai recommends a complete Korean skincare routine tailored to the user's specific acne challenges, skin type, and skin sensitivity.

![image_alt](https://github.com/lukietee/hackne.ai/blob/2ada34c3d90dadf8538dd3a03bbc177937f2b34b/acne5%20(1).jpg)

**Frontened and UI/UX**

hackne.ai is made up of two components: the skin survey and the physical skin scan. All web pages were initially designed in Figma, a design tool used for both mobile and web app development. The web pages were then implemented in HTML, CSS for styling, and Flask (Python). In the skin survey, the user is prompted questions asking their gender, skin type, skin sensitivity, etc. The physical face scan prompts the user to upload a face scan of their acne. Both inputs from the skin survey and physical skin scan are used in the selection of skincare products.

![image_alt](https://github.com/lukietee/hackne.ai/blob/41e5066743ae7f1ec1f2a441c678e218b7616fe3/acne1%20(1).jpg)

**Backend**

hackne.ai was trained using the Ultralytics YOLOv11 object classification model. It was trained on the Acne04 dataset, a reputable annotated dataset cited by 11 studies in various reputable journals. In total, the model took 7 hours to train. hackne.ai recommends products based on a "skin severity score". The trained YOLOv11 model is able to detect different types of skin challenges, such as pimples, scars, whiteheads, and blackheads, and will give the user a score from 1 - 20 based on the amount detected (20 being most severe). 

![image_alt](https://github.com/lukietee/hackne.ai/blob/d7d8437e6daa7d1513511ee76e9c9cee749bff29/acne3%20(1).jpg)

Depending on the skin severity score the user receives, hackne.ai would recommend different products of different intensities. Those who are struggling more with acne may be recommended products that use active acne fighting ingredients such as benzoyl peroxide and salicylic acid, while lower skin severity scores would be recommended less intense products. hackne.ai recommends an AM/PM face wash, moisturizer, and sunscreen.

![image_alt](https://github.com/lukietee/hackne.ai/blob/4dffa4bc7cd811320d05c3d059827900a71a3f61/AcneCredits%20(1).png)
![image_alt](https://github.com/lukietee/hackne.ai/blob/535dbfcce7d73fe4c83602037cf8c1145a9b1f07/acne7%20(1).jpg)

hackne.ai at the 2024 HackCC Hackathon
