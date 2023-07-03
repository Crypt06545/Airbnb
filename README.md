# Full Stack Airbnb Clone with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth 2023


<table>
    <tr>
        <td>
<a href="#"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="" width="30" height="30" /></a>
        </td>
                <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/183096870-fdf58e59-d78c-44f4-bd1c-f9033c16d907.png" alt="Google" width="30" height="30" /></a>
        </td>
                        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/179383376-874f547c-4e6f-4826-850e-706b009e7e2b.png" alt="" width="30" height="30" /></a>
        </td>
                              <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/181918664-569af962-756c-438c-b350-294f042e6f61.png" alt="" width="30" height="30" /></a>
        </td>
                        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/180462270-ea4a249c-627c-4479-9431-5c3fd25454c4.png" alt="" width="30" height="30" /></a>
        </td>
                                <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/185779974-a31a9f47-f8d3-42ea-b7f8-4a2971774615.png" alt="" width="30"height="30"/></a>
        </td>
                                      <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/229775276-a7cb148b-7fbd-4334-a07f-f2223bc49f62.png" alt="" width="30"height="30"/></a>
        </td>
      <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/204170976-0e5c6e2a-2b41-483d-adbd-d5d1e40b8d15.png" alt="" width="30"height="30"/></a>
        </td>
        <td>
<a href="#"><img src="https://user-images.githubusercontent.com/99184393/214867309-7b59fa0e-c872-484e-bc8f-462896c54d2a.png" alt="" height="30"/></a>
        </td>
    </tr>
</table>

Features:

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Credential authentication
- Google authentication
- Github authentication
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
- For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- Shareable URL filters

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/Crypt06545/Airbnb-Clone.git
```

## Sneak Peek of Home Page 🙈 :
![home](images/222.png)

<table>
  <tr>
    <td><img src="images/226.png" alt="mockup" /></td>
    <td><img src="images/227.png" alt="mockups" /></td>
  </tr>
  <tr>
    <td><img src="images/226.png" alt="mockup" /></td>
    <td><img src="images/229.png" alt="mockups" /></td>
  </tr>
</table>


### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

### Setup Prisma

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```

