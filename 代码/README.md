# KITVAULT

A three page football shirt shop built with HTML and CSS only, made for the DIG0011T1AE web site project. No JavaScript anywhere.

## Pages

| File | What it does |
| --- | --- |
| `index.html` | Home: hero picture, four reasons to buy, four shirts, form for a sold-out size |
| `shop.html` | Six shirts with stock badges, plus the size table (`#size-guide`) |
| `customise.html` | Name, number, size and the price list before ordering |

## Other files

- `style.css` — the only stylesheet, shared by all three pages, media queries included.
- `images/` — three drawings. The `.jpg` files are what the pages load; the `.png` files are the larger originals.

## How to open it

Double click `index.html`, or run a small server in this folder:

```
python -m http.server 8000
```

then open `http://localhost:8000`.

## How it was made

The plan, the colours and the layout come from `ALLKITE.pdf`. The text and the code were drafted with an AI assistant (Doubao), then read, corrected and tested by the student. All three pictures are drawings, not club photos, and the stock numbers and prices are example data for the course.

## What is not implemented

There is no JavaScript, so the club filters do not filter, the total is written in the HTML instead of being calculated, and there is no basket or payment. The two forms send the message with `mailto:` so the page still does one useful thing without a server.
