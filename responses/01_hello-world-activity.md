## Step 2: Update Hello World
Let's modify the program a bit to output something else to our terminal.

### :keyboard: Activity: Replace `Hello World!` to `Hello <YOUR_NAME>`
1. In `src/01_hello-world/main.go`, replace line 6 text`Hello World!` to `Hello <YOUR_NAME>!` e.g.
    ```go
    fmt.Println("Hello John!")
    ```
2. Save the file
3. Run the program with `go run src/01_hello-world/main.go`
4. Stage, commit and push your changes to `changes` branch
    ```
    git add src/01_hello-world/main.go
    git commit -m "Replce Hello World"
    git push
    ```