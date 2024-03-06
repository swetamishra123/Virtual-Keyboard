# Virtual Keyboard using ReactJS

This project implements a virtual keyboard using ReactJS, allowing users to interact with the keyboard by clicking on keys. The interface responds accordingly, providing a seamless typing experience. The project utilizes functional components and manages state to handle keypress and character input logic using JSX.

## Technologies Used/Prerequisites

- ReactJS
- CSS
- JSX
- Functional Components in React

## Approach/Functionalities

A virtual keyboard serves as a software-based input interface that emulates a physical keyboard on a digital device. Key functionalities include:

- **User Input Simulation:** Enables users to input text and commands by clicking on virtual keys, replicating physical keyboard functionality.
- **Accessibility:** Enhances accessibility for individuals with physical disabilities by offering alternative input methods.
- **Security:** Virtual keyboards can provide secure data entry, guarding against keyloggers and other security threats.
- **Integration:** They can be seamlessly integrated into various applications such as kiosks, touch-screen devices, and software interfaces to facilitate text input and interaction.

## Project Structure

```
project/
│
├── public/
│   └── index.html
│
├── src/
│   ├── components/
│   │   ├── Keyboard.js
│   │   └── Keyboard.css
│   │
│   ├── App.js
│   └── index.js
│
└── package.json
```

## Steps to create the application

1. **Set up React project:**
   Create a new React project using the following command:
   ```bash
   npx create-react-app my-virtual-keyboard
   ```

2. **Navigate to project folder:**
   Change directory to the project folder:
   ```bash
   cd my-virtual-keyboard
   ```

3. **Create components folder:**
   Inside the `src` directory, create a folder named `components`:
   ```bash
   mkdir src/components
   ```

4. **Add files:**
   Inside the `components` folder, add two new files:
   - `Keyboard.js`
   - `Keyboard.css`

5. **Import icon pack:**
   In the `index.html` file located in the `public` folder, import the icon pack within the `<head>` tag:
   ```html
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
   ```

6. **Code Example:**
   Below is an example code snippet for each file:
   - `index.html`: Automatically created file in the public folder. Just import the icon pack in its `<head>` tag.
   - `App.js`: Imports the Keyboard component and exports it.
   - `Keyboard.js`: Contains logic for the virtual keyboard, keypress, and input text block with state variable.
   - `Keyboard.css`: Contains the design of the virtual keyboard elements.

## License

This project is licensed under the [MIT License](LICENSE).
