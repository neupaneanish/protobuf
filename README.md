# Portfolio Protobuf Engine

###### Developed by [Anish Neupane](https://neupaenanish.com.np)

This repository serves as the **Single Source of Truth (SSOT)** for the entire Portfolio microservices ecosystem. It
centralizes all gRPC interface definitions, message schemas, and API validation contracts to guarantee compile-time type
safety across all system boundaries.

---

## Ecosystem Architecture Matrix

This matrix tracks the structural schema completion for external edges, internal gateways, and root services.

### External Authentication (Public Face)

- [x] **Authentication**
    - [x] `Login`
    - [x] `LoginTwoFactor`
    - [x] `ForgetPassword`
    - [x] `Verification`
    - [x] `ResetPassword`
    - [x] `AccountVerification`
    - [x] `ResendAccountVerification`
    - [x] `Refresh`

---

### Internal Gateway

- [x] **Authentication**
    - [x] `PasswordVerification`
    - [x] `PasswordSessionVerification`
    - [x] `ChangePassword`
    - [x] `EnableTwoFactor`
    - [x] `ConfirmTwoFactor`
    - [x] `Role`
    - [x] `Profile`
    - [x] `Logout`
- [X] **Profile**
    - [X] **Profile**
        - [X] `Create` | `Get` | `Update`
    - [X] **About**
        - [X] `Create` | `Get`
    - [X] **Domain**
        - [X] `Create` | `Get` | `Verify` | `Delete` | `List`
    - [X] **Education**
        - [X] `Create` | `Get` | `Update` | `Delete` | `List`
    - [X] **Experience**
        - [X] `Create` | `Get` | `Update` | `Delete` | `List`
    - [X] **Icons**
        - [X] `List`
    - [X] **Social**
        - [X] `Create` | `Update` | `Delete` | `List`

---

### Root

- [x] **Authentication**
    - [X] `Update Role`
    - [X] `Update Status`
    - [X] `User`
    - [X] `Users`
- [X] **Profile**
    - [X] **Profile**
        - [X] `Get` | `Update`
    - [X] **About**
        - [X] `Get` | `Update`
    - [X] **Domain**
        - [X] `Get` | `List`
    - [X] **Education**
        - [X] `Get` | `Update` | `List`
    - [X] **Experience**
        - [X] `Get` | `Update` | `List`
    - [X] **Icons**
        - [X] `Create`| `Update` | `Get` | `Delete` | `List`
    - [X] **Nameservers**
        - [X] `Create`| `Get` | `Delete` | `List`
    - [X] **Social**
        - [X] `Update` | `List`

---

## [License](LICENSE)