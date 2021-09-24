# Alex Nguyen's User Page

##### index
[me as a programmer](#About-me-(as-a-programmer))

[me as a person](#About-me-(as-a-person))

## About me (as a programmer)

Hello! I am a Computer Engineering major at UCSD in ERC in my 3rd year as an 
undergraduate. 

I don't have much experience in the industry and outside of classes I've only
one hackathon at SDHacks and was fortunate enough to be a developer intern at 
**San Diego Supercomputer Center's** *Research-Data-Services* division under the 
supervision of Ryan Nakashima. I worked on a project with 6 other members and 
learned a lot during my time there in the Summer of 2021.

In my experience, my preferred programming languages are Java, Python, C++, and 
C. 

I care about coding style since I've seen first hand how it can affect readability.
On a project I worked on, there was a fellow developer who didn't indent or kept
a SQL statement within a column limit and instead wrote it all on one line making
statement go very far horizontally; it was hard to read and I did not enjoy scrolling to the left and right to read his code. For example, instead of writing:

```
const stmt = this.db.prepare('SELECT ' +
            'u.profile_picture, fd.drink_id, fd.date, f.friend_uid, d.* ' +
            'FROM (((fav_drinks fd ' +
            'INNER JOIN friends f ON fd.uid = f.friend_uid)' +
            'INNER JOIN users u ON f.friend_uid = u.uid) ' +
            'INNER JOIN drinks d USING(drink_id)) ' +
            "WHERE f.uid = ? AND status = 'friends' " +
            \`AND date > DATE('now', '-${DISPLAY_HOME_WINDOW}') \` +
            'ORDER BY date COLLATE NOCASE DESC')
```

he would write it all on one line:

`const stmt = this.db.prepare('SELECT u.profile_picture, fd.drink_id, fd.date, f.friend_uid, d.* FROM (((fav_drinks fd INNER JOIN friends f ON fd.uid = f.friend_uid) INNER JOIN users u ON f.friend_uid = u.uid) INNER JOIN drinks d USING(drink_id)) WHERE f.uid = ? AND status = 'friends' AND date > DATE('now', '-${DISPLAY_HOME_WINDOW}') ORDER BY date COLLATE NOCASE DESC')`

This of course looks horrible so in the words of one of my friends:
> I like spaghetti just not in my code

I am always looking for more opportunities to grow so if you know of one, please
let me know! Here is my [LinkedIn:](https://www.linkedin.com/in/nguyentalex/)

## About me (as a person)

If you were to find me anywhere in my freetime it will probably be at home playing
video games LOL. 

My favorite games include Valorant, Genshin Impact, Elder Scrolls V: Skyrim, TF2,
and Pirate101. Sadly, the latter two are no longer supported by their developers
and have received very little updates driving me to different games. I love 
Skyrim because of the roleplay potential and the many different things I can do.
Valorant is fun because I like to play FPS games and I prefer it over others.
Genshin Impact is a free to play game that has quite astonishing visuals and is
very colorful so I like playing it and grinding for those limited time characters xd

Apart from video games, I love food! I am open to trying new dishes and cuisines
within a certain boundary and have found new favorites as a result. My favorite
foods are Korean Soft Tofu Soup, Sizzling Pot King's Stir Fry Pots, Sushi, Pho,
Spicy Pasta, and other rice dishes!

I am a cat person and proud of it. They smell better (as long as you maintain
basic hygiene) and are so adorable and cute! My family recently got a few kittens
and there are some in the CATS folder. Here's [two of them sleeping!]("./CATS/Kittens sleeping next to Alum Foil.jpg")