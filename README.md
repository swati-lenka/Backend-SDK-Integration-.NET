# PhonePe .NET Backend SDK (v2)

[![NuGet Version](https://img.shields.io/nuget/v/PhonePe.Sdk.svg)](https://www.nuget.org/packages/PhonePe.Sdk/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An unofficial, complete .NET SDK for server-side integration with the PhonePe Payment Gateway (v2). This library simplifies the entire payment lifecycle, handling authentication, payment initiation, status checks, and secure JWT webhook verification for your .NET applications.

## Features

-   **Simplified Payment Initiation:** Create new payment requests with a simple method call.
-   **Payment Status Verification:** Easily check the status of any transaction.
-   **Refund Support:** Programmatically initiate refunds.
-   **Secure Webhook Handling:** Includes a utility to verify the JWT signature from incoming v2 webhook notifications using your `ClientSecret`.
-   **Modern .NET:** Built with modern `async/await` patterns.

## Prerequisites

-   .NET 6.0 or higher
-   A PhonePe Merchant Account with active **Backend SDK** credentials:
    -   `CLIENT_ID`
    -   `CLIENT_SECRET`
    -   `CLIENT_VERSION`
   
## Installation

Install the package via the .NET CLI or NuGet Package Manager:

```bash
dotnet add package PhonePe.Sdk
