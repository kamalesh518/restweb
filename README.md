# Ex.07 Restuarant Website
## Date:20/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
Home.html

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lovely Moon — Home</title>
  <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
  <header class="nav">
    <div class="wrap inner">
      <div class="brand">Lovely</div>
      <nav class="links">
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <img src="rest.jpg" alt="Restaurant Banner">
    <div class="overlay"></div>
    <div class="content">
      <span class="badge">Since 1998</span>
      <h1>Crafted Flavors, Warm Hospitality</h1>
      <p class="subtitle">Seasonal ingredients with wood-fired classics.</p>
      <a class="btn primary" href="menu.html">Explore Menu</a>
    </div>
  </section>

  <section class="section">
    <div class="wrap grid3">
      <div class="card"><h3>Wood-Fired Ovens</h3><p>Perfect char & chewy crusts.</p></div>
      <div class="card"><h3>Local Produce</h3><p>Fresh & seasonal.</p></div>
      <div class="card"><h3>Cozy Atmosphere</h3><p>Soft lighting & warm vibes.</p></div>
    </div>
  </section>

  <footer>
    <div class="wrap">© 2025 Lovely Moon — Designed by <strong>Parani Bala M</strong></div>
  </footer>
</body>
</html>

Menu.html

<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Lovely Moon — Menu</title>
    <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
    <header class="nav">
        <div class="wrap inner">
            <div class="brand">Lovely Moon</div>
            <nav class="links">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="#">Administration</a>
                <a href="#">Contact</a>
            </nav>
        </div>
    </header>
    <main class="wrap section">
        <h2 class="section-title">Menu</h2>
        <section class="menu-grid">
            <article class="item">
                <img src="pizza.jpg" alt="Margherita Pizza">
                <div class="pad">
                    <div class="row">
                        <div class="name">Margherita Pizza</div>
                        <div class="price">₹699</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="bbqc.jpg" alt="BBQ Chicken">
                <div class="pad">
                    <div class="row">
                        <div class="name">BBQ Chicken</div>
                        <div class="price">₹799</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="arr.jpg" alt="Arrabbiata">
                <div class="pad">
                    <div class="row">
                        <div class="name">Arrabbiata</div>
                        <div class="price">₹649</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="carbo.jpg" alt="Carbonara">
                <div class="pad">
                    <div class="row">
                        <div class="name">Carbonara</div>
                        <div class="price">₹749</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="salmon.jpg" alt="Grilled Salmon">
                <div class="pad">
                    <div class="row">
                        <div class="name">Grilled Salmon</div>
                        <div class="price">₹1099</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="butter.jpg" alt="Butter Chicken">
                <div class="pad">
                    <div class="row">
                        <div class="name">Butter Chicken</div>
                        <div class="price">₹799</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="vegb.jpg" alt="Veg Biryani">
                <div class="pad">
                    <div class="row">
                        <div class="name">Veg Biryani</div>
                        <div class="price">₹649</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="pan.png" alt="Paneer Tikka">
                <div class="pad">
                    <div class="row">
                        <div class="name">Paneer Tikka</div>
                        <div class="price">₹599</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="cae.jpg" alt="Caesar Salad">
                <div class="pad">
                    <div class="row">
                        <div class="name">Caesar Salad</div>
                        <div class="price">₹449</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="gre.jpg" alt="Greek Salad">
                <div class="pad">
                    <div class="row">
                        <div class="name">Greek Salad</div>
                        <div class="price">₹499</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="lava.jpg" alt="Lava Cake">
                <div class="pad">
                    <div class="row">
                        <div class="name">Lava Cake</div>
                        <div class="price">₹349</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
            <article class="item">
                <img src="gulab.jpg" alt="Gulab Jamun">
                <div class="pad">
                    <div class="row">
                        <div class="name">Gulab Jamun</div>
                        <div class="price">₹199</div>
                    </div>
                    <div class="small">House favorite crafted with seasonal ingredients.</div>
                    <a class="btn" style="width:max-content;margin-top:6px" href="#">Add to Order</a>
                </div>
            </article>
        </section>
    </main>
    <footer>
        <div class="wrap">© 2025 Lovely Moon — Designed by <strong>Parani Bala M</strong></div>
    </footer>
</body>

</html>

Administration.html

<!doctype html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lovely — Administration</title>
  <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
  <header class="nav">
    <div class="wrap inner">
      <div class="brand">Lovely Moon</div>
      <nav class="links">
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>

  <main class="wrap section">
    <h2 class="section-title">Administration</h2>
    <p class="small" style="margin-bottom:12px">Meet the core team behind the flavor and the service.</p>

    <section class="menu-grid">
      <article class="item">
        <img src="sanji.jpg" alt="Head Chef">
        <div class="pad">
          <div class="row">
            <div class="name">Mr. Vinsmoke Sanji</div>
            <div class="small">Head Chef</div>
          </div>
          <div class="small">Leads the kitchen, menu R&D, and training.</div>
        </div>
      </article>

      <article class="item">
        <img src="koruyim.jpg" alt="Assistant Chef">
        <div class="pad">
          <div class="row">
            <div class="name">Ms. Ko Yu Rim</div>
            <div class="small">Asst Chef</div>
          </div>
          <div class="small">Runs prep, quality checks, and line coordination.</div>
        </div>
      </article>

      <article class="item">
        <img src="luffy.jpg" alt="Restaurant Manager">
        <div class="pad">
          <div class="row">
            <div class="name">Mr. Luffy Taro</div>
            <div class="small">Restaurant Manager</div>
          </div>
          <div class="small">Guest experience, floor operations, and events.</div>
        </div>
      </article>
    </section>
  </main>

  <footer>
    <div class="wrap">© 2025 Lovely Moon — Designed by <strong>Parani Bala M</strong></div>
  </footer>
</body>

</html>

contact.html

<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Lovely Moon — Contact</title>
    <link rel="stylesheet" href="assets/styles.css">
</head>

<body>
    <header class="nav">
        <div class="wrap inner">
            <div class="brand">Lovely Moon</div>
            <nav class="links">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="administration.html">Administration</a>
                <a href="contact.html">Contact</a>
            </nav>
        </div>
    </header>

    <section class="hero" style="min-height:48vh">
        <img src="assets/images/con.jpg" alt="Contact hero">
        <div class="overlay"></div>
        <div class="content">
            <span class="badge">We'd love to hear from you</span>
            <h1>Contact & Reservations</h1>
            <p class="subtitle">Questions, events, or bookings — drop us a line.</p>
        </div>
    </section>

    <main class="wrap section">
        <div class="grid3">
            <div class="card">
                <h3>Address</h3>
                <p class="small">Lovely Moon, 21 MG Road, Indiranagar<br>Bengaluru, Karnataka 560038, India</p>
                <h3>Hours</h3>
                <p class="small">Mon–Sun: 11:30–22:30</p>
            </div>
            <div class="card">
                <h3>Contact</h3>
                <p class="small"><strong>Phone:</strong> <a href="tel:+918045001234">+91 80450 01234</a></p>
                <p class="small"><strong>Email:</strong> <a
                        href="mailto:reservations@lovelymoon.example">reservations@lovelymoon.example</a></p>
            </div>
            <div class="card">
                <h3>Social</h3>
                <p class="small">Instagram • Facebook • Maps</p>
                <p class="small">Follow for specials and events.</p>
            </div>
        </div>

        <div class="card" style="margin-top:16px">
            <h3 style="margin:0 0 8px">Send us a message</h3>
            <form onsubmit="event.preventDefault(); alert('Thanks! We will get back to you soon.');">
                <div class="grid3" style="grid-template-columns:1fr 1fr 1fr;gap:12px">
                    <p><input placeholder="Name"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                    <p><input placeholder="Email" type="email"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                    <p><input placeholder="Phone"
                            style="width:100%;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)">
                    </p>
                </div>
                <p><textarea placeholder="Message"
                        style="width:100%;min-height:140px;padding:10px 12px;border-radius:12px;border:1px solid rgba(255,255,255,.18);background:rgba(255,255,255,.06);color:var(--ink)"></textarea>
                </p>
                <p><button class="btn primary" type="submit">Send</button></p>
            </form>
        </div>
    </main>

    <footer>
        <div class="wrap">© 2025 Lovely Moon — Designed by <strong>Parani Bala M</strong></div>
    </footer>
</body>

</html>

```

## OUTPUT:
<img width="1085" height="617" alt="Screenshot 2025-11-20 101903" src="https://github.com/user-attachments/assets/db12b12f-2dab-4dae-a794-aa4284fd4910" />

<img width="1130" height="622" alt="Screenshot 2025-11-20 101915" src="https://github.com/user-attachments/assets/73d9444a-3cad-424f-880b-35b16ab49bb8" />

<img width="1089" height="612" alt="Screenshot 2025-11-20 101924" src="https://github.com/user-attachments/assets/5027a965-5e24-4bcf-a101-6fa37d40c4b6" />

<img width="1102" height="585" alt="Screenshot 2025-11-20 101934" src="https://github.com/user-attachments/assets/a53d9496-eada-4447-bea1-4fdca7140f55" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
