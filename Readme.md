#### Step 1: Download and install .Net Core 5.0 (or higher)

[Download link](https://dotnet.microsoft.com/en-us/download)

#### Step 2: Add environment variables

- Go to the appsetting.json file (create new file and copy contents in appsetting.json.example)
- Added values for PayOS payment gateway environment variables
  - "PAYOS_CLIENT_ID": "{your id}",
  - "PAYOS_API_KEY": "{your api key}",
  - "PAYOS_CHECKSUM_KEY": "{your checksum key}",

#### Step 3: Run

Open terminal to root folder:
Run:

```
dotnet run
```
