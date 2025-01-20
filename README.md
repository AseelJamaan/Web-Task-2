# README for Robot Direction Control Project

## Project Overview
This project allows users to control a robot’s movement through a web interface. Commands like Forward, Backward, Left, Right, and Stop are stored in a database, and the latest command can be retrieved and displayed.

---

## Features
1. **Control Panel**: Web interface with direction buttons.
2. **Database**: Stores direction commands.
3. **Retrieve Direction**: PHP page shows the latest command.

---

## Technologies Used
- **HTML/CSS**: Web interface.
- **PHP**: Backend functionality.
- **MySQL**: Database.
- **XAMPP**: Local server.

---

## Setup Steps
1. **XAMPP**: Start Apache and MySQL.
2. **Database**: Create `robot_control` database with `direction` table (`id` INT, `value` VARCHAR(10)).
3. **Upload Files**: Place files in `htdocs`.
4. **Run**:
   - Control Panel: `http://localhost/robot_control/control_panel.html`
   - Latest Direction: `http://localhost/robot_control/get_direction.php`

---

## Example
- Click "Forward," it will save `f` in the database.
- Retrieve and display: "Current Direction: f."

---
