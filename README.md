# Motorsport-DB - Drivers Directory

## Contribution Guidelines

Welcome to the **Drivers** repository of Motorsport-DB! This repository is dedicated to storing information about racing drivers in a structured format. We encourage contributions from the community to help build a comprehensive database.

### ✅ **General Rules**
- All **images** used for drivers must be **free of copyright** or your own property.
- All **JSON files** must be **valid** and follow the correct format.
- The information provided **must be as accurate as possible**, including race results, birthdates, and other relevant details.
- Contributions **do not need to be complete**; even partial information is valuable!
- Any missing or incorrect information should be updated through pull requests (PRs).

### 🛠 **How to Contribute**
1. **Fork the repository** to your account.
2. **Clone the forked repository** to your local machine.
3. **Create a new branch** with a descriptive name.
4. **Add or update JSON files** in the `drivers/` directory.
5. **Commit your changes** (see commit rules below).
6. **Push your branch** and open a pull request (PR) against the `main` branch.
7. **Wait for review and approval** before merging.

### 📜 **JSON Formatting Guidelines**
Each driver should have a JSON file named `firstname_lastname.json` (e.g., `doriane_pin.json`).

Example JSON structure:
```json
{
    "firstName": "Doriane",
    "lastName": "Pin",
    "Nickname": "the Pocket Rocket",
    "dateOfBirth": "2004-01-06",
    "picture": "doriane_pin.jpg",
    "country": "France",
    "seasons": {
        "2024": {
            "F1 Academy": {
                "standing": {
                    "position": 2,
                    "points": 217
                },
                "Jeddah": {
                    "Free practice": {
                        "position": 1,
                        "fastest_lap": "2:04.889",
                        "other_info": {
                            "fastest_speed": "177.969 km/h",
                            "laps": 15
                        },
                        "team": "PREMA_Racing"
                    },
                    "Qualifying 1": {
                        "position": 1,
                        "fastest_lap": "2:03.472",
                        "other_info": {
                        },
                        "team": "PREMA_Racing"
                    },
                    "Qualifying 2":
                        {
                            "position": 1,
                            "fastest_lap": "2:03.699",
                            "other_info": {
                            },
                        "team": "PREMA_Racing"
                        },
                    "Race 1": {
                        "position": 1,
                        "points": 27,
                        "fastest_lap": "2:04.678",
                        "other_info": {
                            "fastest_speed": "165.005 km/h",
                            "laps": 12
                        },
                        "team": "PREMA_Racing"
                    },
                    "Race 2": {
                        "position": 9,
                        "points": 5,
                        "fastest_lap": "2:04.259",
                        "other_info": {
                            "fastest_speed": "148.378 km/h",
                            "laps": 13
                        },
                        "team": "PREMA_Racing"
                    }
                }
            }
        }
    }
}
```

### 🔍 **Commit & PR Rules**
- **No direct pushes to `main`** – Always work through **pull requests**.
- **Commit messages should be signed** (preferred) and structured as follows:
  - **First line:** A concise summary of changes (max 70 characters).
  - **Commit description:** A detailed explanation listing all modifications.
  
Example commit message:
```
Added new driver (Doriane Pin)

- Created `doriane_pin.json` with Jeddah result
```

### 🚀 **Need Help?**
If you're unsure about formatting or contribution guidelines, feel free to open an issue in the repository. We appreciate all contributions to make Motorsport-DB the most complete racing database!

Thank you for contributing! 🏎️

