# BlankOn Home & News

BlankOn News Website, providing news to the community.

# TODO

* Halaman Menjadi Sponsor? - Translate | disable menu (done)
* Halaman Menjadi Mitra? - Translate | disable menu (done)
* Rilis berita server baru (estu)
* Deploy Production (samsul)

## Sponsor Level
* Peta Level
- badak host | https://www.hostbadak.com/
- radnet | https://www.rad.net.id/
* Tera Level
- Datautama | https://datautama.net.id/
- Fans | https://sepatuku.fans.co.id/
- Btech | https://btech.id/

## How to submit a new post?

1. Create a new markdown file in `_posts` directory. File name should follow `yyyy-mm-dd-title.md` format. For example, `2020-02-27-my-first-post.md`. You can start by clicking [this link](https://github.com/tuanpembual/blankon-beranda/blob/master/_posts/2018-08-20-bananas.md).

2.  Please use an illustration image with at least 1153x505px size. It should be placed as well in its own directory named with the date format `yyyy-mm-dd` in `/assets/posts`. For example: `/assets/posts/2020-12/boni.png`. If you need help with creating some approriate image feel free to ask in Tim Kesenian.

3. Write content. You can start with the following template:
    ```
    ---
    author: Maskot Boni
    date: 2020-12-27 19:27:17+00:00
    layout: post
    license: CC-BY-SA-3.0
    title: My First Post
    image: /assets/posts/2020-12/omw.png
    categories:
    - Announcements
    tags:
    - infrastructure
    - websites
    ---

    Write you post in Markdown and HTML...

    ```
    The date and time you set here, in the header, will be the date and time your article, once merged, will be published and available on [news.opensuse.org](https://news.opensuse.org). If you set the current day's date, be aware that there might be up to 2 hours delay between the time the PR got accepted and the time it actually gets picked up by the server.

4. Save the file and create a pull request. You can find the button at page bottom.

## How to build?

In order to run ``bundle`` the two following addional packages are needed: ``'rubygem(bundler)' ruby-devel``.
```bash
bundle install --path vendor/bundle
bundle exec jekyll build
```

Resulting site will be in `_site` directory.

## How to serve locally?

```bash
bundle install --path vendor/bundle
bundle exec jekyll serve
```

Visit <http://127.0.0.1:4000/> in your browser.

## How to use emojis in your blog post?

We are using the [Jemoji plugin](https://github.com/jekyll/jemoji), which allows you to use GitHub like syntax for emojis in your blog posts.
For example, `it's raining :cat:s and :dog:s!`, will be rendered as:

> it's raining :cat:s and :dog:s!

