# challange-8
# BCR API

Di dalam repository ini terdapat implementasi API dari Binar Car Rental.
Tugas kalian disini adalah:
1. Fork repository
2. Tulis unit test di dalam repository ini menggunakan `jest`.
3. Coverage minimal 70%

Good luck!

## Deployment URL
- https://challenge-chapter-8-bregsi.up.railway.app/

## The Lastest Testing Result (on Railway.app)
File                          | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
------------------------------|---------|----------|---------|---------|--------------------------------
All files                     |   87.81 |    66.66 |   84.61 |   88.76 |
 app                          |   97.61 |      100 |      50 |     100 |
  index.js                    |   93.33 |      100 |       0 |     100 |
  router.js                   |     100 |      100 |     100 |     100 |
 app/controllers              |   80.66 |    78.12 |   83.33 |   81.75 |
  ApplicationController.js    |   93.33 |      100 |      80 |   93.33 | 6
  AuthenticationController.js |   87.32 |    81.25 |     100 |   87.32 | 33,81,115,123-125,131-133
  CarController.js            |   68.33 |       60 |   66.66 |   70.68 | 37-50,80-82,99-114,124-125,145
  index.js                    |     100 |      100 |     100 |     100 |
 app/errors                   |   92.85 |      100 |   78.57 |   92.85 |
  ApplicationError.js         |     100 |      100 |     100 |     100 |
  CarAlreadyRentedError.js    |      50 |      100 |       0 |      50 | 5-9
  EmailAlreadyTakenError.js   |     100 |      100 |     100 |     100 |
  EmailNotRegisteredError.js  |     100 |      100 |     100 |     100 |
  InsufficientAccessError.js  |     100 |      100 |     100 |     100 |
  NotFoundError.js            |     100 |      100 |     100 |     100 |
  RecordNotFoundError.js      |   66.66 |      100 |       0 |   66.66 | 5
  WrongPasswordError.js       |     100 |      100 |     100 |     100 |
  index.js                    |     100 |      100 |     100 |     100 |
 app/models                   |   97.61 |    66.66 |     100 |   97.61 |
  car.js                      |     100 |      100 |     100 |     100 |
  index.js                    |      95 |    66.66 |     100 |      95 | 13
  role.js                     |     100 |      100 |     100 |     100 |
  user.js                     |     100 |      100 |     100 |     100 |
  usercar.js                  |     100 |      100 |     100 |     100 |
 config                       |     100 |    14.28 |     100 |     100 |
  application.js              |     100 |       50 |     100 |     100 | 3
  database.js                 |     100 |        0 |     100 |     100 | 2-6

- Test Suites: 3 passed, 3 total
- Tests:       23 passed, 23 total
- Snapshots:   0 total
- Time:        5.103 s
