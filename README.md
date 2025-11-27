
**Place Recognition Using Deep Learning and Gradio**

This project predicts famous places in India from an uploaded image using a trained deep learning model. It also fetches a short description of the predicted place from Google Search and displays it inside a simple Gradio interface.

**Features**

Upload an image and get the predicted place name.

Fetches a short description of the place using Google search results.

Displays prediction, description, and a link for more information.

Easy-to-use Gradio web interface.

Works with 29+ popular Indian landmarks.

**Technologies Used**

TensorFlow / Keras (model training and prediction)

Gradio (web interface)

BeautifulSoup (web scraping for details)

Requests (HTTP requests)

PIL & NumPy (image preprocessing)

Google Colab + Google Drive (model storage and execution)

**Supported Place Classes**

Taj Mahal, Qutub Minar, India Gate, Red Fort, Hawa Mahal, Golden Temple, Jaisalmer Fort, Lotus Temple, Humayun's Tomb, Charminar, Meenakshi Temple, Tanjore Big Temple, Marina Beach, Mysore Palace, Hampi Monuments, Golconda Fort, Ramoji Film City, Kerala Backwaters, Varkala Beach, Fort Kochi, Munnar Tea Gardens, Coorg, Mahabalipuram, Rameshwaram, Kodaikanal, Ooty, Bandipur National Park, Periyar Wildlife Sanctuary, Vivekananda Rock Memorial.

**How It Works**

The model is loaded from Google Drive.

The uploaded image is resized to 224x224, converted to an array, normalized, and passed to the model.

The predicted class is mapped to a place name.

A Google search query is executed to fetch a short description.

Gradio displays the predicted place with description and a link for more information.

**Usage**

Run the script in Google Colab.
After running, Gradio will generate a shareable URL.
You can open the link in your browser to use the application.

**Folder Structure**

PlaceImages/
├── my_model.h5
├── Taj Mahal/
├── Qutub Minar/
├── India Gate/
└── ... (folders for all places)

Notes

Google scraping may return different results depending on availability.

Best suited for learning, academic projects, and prototype-level applications.

For more stable place information, consider using Wikipedia API or Google Places API.
