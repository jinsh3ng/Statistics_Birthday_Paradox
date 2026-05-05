import kagglehub

# Download latest version
path = kagglehub.dataset_download("mexwell/famous-birthdays")

print("Path to dataset files:", path)