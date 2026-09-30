# ABES Club – College Event Management Website

A lightweight, responsive website for managing and displaying college club events. Built with plain **HTML, CSS and JavaScript**, with no frameworks and no build step.

## How to Access

Open the live site: **https://abes-event-management.onrender.com**

It works in any modern browser (Chrome, Edge, Firefox or Safari), on both desktop and mobile.

## How to Use (Students)

| Page | What you can do |
|------|-----------------|
| **Home** | Read the club intro, see the featured event and the next 3 upcoming events. |
| **Events** | View all events as cards (name, date and time, venue, description). |

**Search and filter:** type in the search box to find events by name, or use the dropdown to filter by category (Tech, Cultural, Sports, Workshop, Social).

**Register for an event:**
1. Click **Register** on an event card.
2. Fill in name, email, college/year and phone number (10 digits).
3. Click **Submit registration**. A confirmation message appears.

Notes: past events show "Closed", and the same email cannot register twice for one event.

## How to Use (Admin)

1. Open the **Admin** tab.
2. Log in with the demo password: `admin123`.

**Events tab**
- **Add event:** click **+ Add event**, fill in the details, and save. Tick *Featured* to show it on the Home page.
- **Edit:** click **Edit** on any row, change the details, and save.
- **Delete:** click **Delete** and confirm. This also removes that event's registrations.

**Registrations tab**
- View every registered student with their details and the event they signed up for.
- **Search** by name, email or college.
- **Filter** by event using the dropdown.
- Click **Remove** to delete a registration.

## Features

- Fully responsive layout for phones, tablets and desktops
- Light animations (page fade-in, card hover, toast messages)
- Automatic dark mode, following the device setting
- Form validation for email, phone and duplicate registrations
- Sample events included, so the site is not empty on first open

## Customizing

- **Club name:** search for `ABES` in the file and replace it.
- **Colors:** edit the variables under `:root` at the top of the `<style>` section.
- **Sample events:** edit the `seed` function in the script.
- **Admin password:** change `admin123` in the login handler near the bottom of the script.

## Tech Stack

HTML5, CSS3 (Grid and Flexbox), Vanilla JavaScript, and `localStorage` for saving data.

## Important Notes

- Data is stored in the browser (`localStorage`). Events and registrations are saved per browser and are not shared between users or devices.
- The admin login is a front-end demo, not real security.
- **Future improvements:** a backend and database (Node.js and MongoDB, or Firebase), real admin authentication, and CSV export of registrations.