This is repository for Exercise 3 Web Client Development(WCD) 

Repository aims to understand how html css works. I added some overlapping code in css to complete and customize the project based on the given ui design.

### Project Structure

```
nama-proyek/
├── images/
│   └── balls.svg
|   └── logo.svg
|   └── whatsapp-icon.svg
|   └── woman.svg
├── index.html
├── css/
├── README.md
└── style.css

```


### What I Changes

#### Chnage on nav element
```css
/* Check margin */
nav {
  font-family: 'Mulish', sans-serif;
  color: #000;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 3rem;
}
```


#### Chnage on av ul element
```css
nav ul {
  display: flex;
  gap: 48px;
  list-style-type: none;
}
```

#### Chnage css on nav ul li a element
```css
/* Check list link style */
nav ul li a {
  text-decoration: none;
  color: #8f8a99;
}

/* Make text bold on hover */
nav ul li a:hover {
  color: #000;
  font-weight: 500;
}
```

#### Chnage css .text h1 and .text h1 span element
```css
/* Check margin and font styling */
.text h1 {
  font-family:'Mulish', sans-serif;
  font-size: 3.1rem;
  font-weight:lighter;
  margin-top: 1.5rem;
}

/* Check font styling */
.text h1 span {
  color: #89c5cb;
  font-weight: 600;
  line-height: 5rem;
}
``` 

#### Change css text p element
```css
/* Check font styling */
.text p {
  font-family: 'Open Sans', sans-serif; 
  color: #acabb5;
  font-size: 1.1rem;
  letter-spacing: 0.05rem;
  margin-top: 1.3rem;
  line-height: 1.7rem;
}
```


#### Change css .text button element

```css
/* Check font styling and make sure the button is rounded */
.text button {
  font-family: 'Open Sans', sans-serif;
  display: flex;
  gap: 8px;
  padding:0.9rem 2.1rem;
  background-color: #69B99E;
  margin-top: 2.8rem;
  color: #F9F9F9;
  border: none;
  align-items: center;
  border-radius: 4px;
  cursor: pointer;
}

/* Handle when user hover on the button */
.text button:hover {
  background-color: #5DC4A2; /* Warna latar belakang saat di-hover */
  transform: scale(1.05);
}
```


#### Change css on footer and footer a element
```css

/* Check the text styling */
footer {
  font-family: 'Open Sans', sans-serif; 
  display: flex;
  justify-content: center;
  color: #2F302F;
}

/* Check the text styling */
footer a {
  color: #000000;
  text-decoration: none;
  font-weight: 700;
}
```