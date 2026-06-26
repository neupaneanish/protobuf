# Portfolio Protobuf Engine

###### Developed by [Anish Neupane](https://neupaenanish.com.np)

This repository serves as the **Single Source of Truth (SSOT)** for the entire Portfolio microservices ecosystem. It
centralizes all gRPC interface definitions, message schemas, and API validation contracts to guarantee compile-time type
safety across all system boundaries.

---

## Ecosystem Architecture Matrix

This matrix tracks the structural schema completion for external edges, internal gateways, and platform root services.

### External Authentication (Public Face)

- [x] **Authentication Core Flow**
    - [x] `Login`
    - [x] `LoginTwoFactor`
    - [x] `ForgetPassword`
    - [x] `Verification`
    - [x] `ResetPassword`
    - [x] `AccountVerification`
    - [x] `ResendAccountVerification`
    - [x] `Refresh`

### Internal Gateway

- [ ] **Account Management**
    - [x] `ChangePassword`
    - [x] `VerifyChangePassword`
    - [x] `ConfirmChangePassword`
    - [x] `EnableTwoFactor`
    - [x] `VerifyTwoFactor`
    - [x] `ConfirmTwoFactor`
    - [x] `DeleteTwoFactor`
    - [x] `ConfirmDeleteTwoFactor`
- [X] **About**
    - [X] `Create` | `Get` | `Update`
- [X] **Domain**
    - [X] `Create` | `Get` | `Update` | `Delete` | `List`
- [X] **Education**
    - [X] `Create` | `Get` | `Update` | `Delete` | `List`
- [X] **Experience**
    - [X] `Create` | `Get` | `Update` | `Delete` | `List`
- [X] **Platform**
    - [X] `List`
- [X] **Profile**
    - [X] `Create` | `Get` | `Update`

### Root / Admin

- [ ] **Root**
    - [ ] `Platform`

---

## [License](LICENSE)