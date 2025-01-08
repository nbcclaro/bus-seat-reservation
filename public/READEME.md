# Bus Seat Reservation System

This is a Bus Seat Reservation System that allows users to check available seats, reserve seats, and take screenshots of the seat layout.

## Prerequisites

- Node.js and npm installed
- XAMPP installed and running
- Git installed

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Create a `screenshots` folder in the project directory:

    ```sh
    mkdir screenshots
    ```

## Running the Server

1. Start the XAMPP Control Panel and ensure Apache is running.

2. Start the Node.js server:

    ```sh
    node server.js
    ```

3. Open your web browser and navigate to:

    ```sh
    http://localhost/bus/bus-seat-reservation/public/index.html
    ```

## Usage

1. Select the travel date and time.
2. Click the "Check Available Seats" button to see the available seats.
3. Click on the seats to select them.
4. Click the "Confirm Reservation" button to reserve the selected seats.
5. Click the "Take Screenshot" button to take a screenshot of the seat layout and save it to the `screenshots` folder.

## Deploying to GitHub

1. Initialize a Git repository:

    ```sh
    git init
    ```

2. Add the remote repository:

    ```sh
    git remote add origin https://github.com/your-username/your-repo-name.git
    ```

3. Add files to staging:

    ```sh
    git add .
    ```

4. Commit the changes:

    ```sh
    git commit -m "Initial commit"
    ```

5. Push to GitHub:

    ```sh
    git push -u origin master
    ```

## Deploying to Netlify

1. **Login to Netlify:**
   - Go to [Netlify](https://www.netlify.com/) and log in.

2. **Create a New Site:**
   - Click on "New site from Git".

3. **Connect to GitHub:**
   - Choose GitHub as your Git provider.
   - Authenticate with GitHub and authorize Netlify to access your repositories.

4. **Select Your Repository:**
   - Select the repository you want to deploy.

5. **Configure Your Build Settings:**
   - **Branch to deploy:** `master` (or the branch you want to deploy)
   - **Build command:** `npm run build` (if you have a build script, otherwise leave it blank)
   - **Publish directory:** [public](http://_vscodecontentref_/1) (or the directory where your `index.html` file is located)

6. **Deploy Site:**
   - Click "Deploy site".

## License

This project is licensed under the MIT License.