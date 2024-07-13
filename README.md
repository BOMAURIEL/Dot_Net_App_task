# Counter App

This Counter App is a simple .NET Blazor application that demonstrates a counter with some CPU and disk-intensive tasks. The app includes functionalities to increment a counter, perform CPU-intensive operations, and simulate disk-intensive tasks by writing data to a file.

## Features

- **Counter:** Increment the counter by 1 or 2.
- **Increment by Loop:** Increment the counter continuously in a loop.
- **CPU Intensive Task:** Simulate a CPU-intensive task.
- **Disk Intensive Task:** Simulate a disk-intensive task by writing data to a file.
- **Log Output:** Display the log of operations with the latest task result at the top.

## Pages

### Home Page
The home page provides an overview of the app and its functionalities. It guides the user to navigate to the counter page to try out the features.

### Counter Page
The counter page allows users to interact with the counter and run CPU and disk-intensive tasks. It includes buttons to increment the counter, start tasks, and view log outputs.

## Usage

1. **Home Page:**
   - Navigate to the home page to read about the app and its functionalities.
   - Click on the link to navigate to the counter page.

2. **Counter Page:**
   - Use the buttons to increment the counter by 1 or 2.
   - Start the continuous increment task and observe the log output.
   - Run the CPU-intensive task and check the result in the log.
   - Perform the disk-intensive task and see the completion message in the log.

## How to Run

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/counter-app.git
    cd counter-app
    ```

2. Build and run the application:
    ```sh
    dotnet build
    dotnet run
    ```

3. Open your browser and navigate to `https://localhost:5001` to see the app in action.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
