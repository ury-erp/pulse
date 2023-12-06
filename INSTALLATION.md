# URY Pulse Installation

**Prerequisite Setup:**
- Before using URY Pulse, ensure you have URY and Frappe HR installed.
- Follow the [URY installation guide](https://github.com/ury-erp/ury/blob/main/INSTALLATION.md) for the installation process.

### To install URY Pulse, follow these steps:

**Create New Site:**

```sh
  $ bench new-site sitename
```
**Install the Frappe HR app to your bench:**

```sh
  $ $ bench get-app hrms
```

**Install the URY Pulse app to your bench:**

```sh
  $ bench get-app ury_pulse https://github.com/ury-erp/pulse.git
```

**To install Frappe HR into site:**

```sh
  $ bench --site sitename install-app hrms
```

**To install URY Pulse into site:**

```sh
  $ bench --site sitename install-app ury_pulse
```

**Migrate the site:**

```sh
  $ bench --site sitename migrate
```