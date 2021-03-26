# 🧠 Face Recognition

This project is what we call a "Hub Experience" in EPITECH. The purpose is to discover something new, explore new technologies and try to learn things that are not in our studies.

With this project I'm discovering the world of AI training. I'm getting the input of my computer camera and training it with an image of me associated to my name. It's then able to recognize me and draw a square around my face.

![](./assets/demo.gif)

## 📃 Prerequisite

1. Python 3.8
2. Pip 20.0
3. A picture of you

## 🏁 Run the project

1. Install dependencies `pip install -r requirements`
2. Put the image of you in the `data` folder
3. Update `main.py` with:
    ```python
    new_image = face_recognition.load_image_file("data/<YOUR_FILE>")
    new_face_encoding = face_recognition.face_encodings(me_image)[0]

    known_face_encodings = [
        ...,
        new_face_encoding
    ]
    known_face_names = [
        ...,
        "<YOUR_NAME>"
    ]
    ```
4. Run the script using `python main.py`

## 🏷️ Author

- [Theo Mazars](https://github.com/theo-mazars)

## 🔓 License

This project is too simple to use a License. Feel free to reuse the code.
