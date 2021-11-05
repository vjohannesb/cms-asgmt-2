# Control Panel / USERS

---

| Username                    | Password      | Access Level                                                          |
| --------------------------- | ------------- | --------------------------------------------------------------------- |
| admin@admin                 | adminadmin    | Everything                                                            |
| editor@editor               | editoreditor  | Root = Articles folder, can write + publish articles                  |
| writer@writer               | writerwriter  | Can write any kind of article (News/Reviews/Premium), but not publish |
| limitedwriter@limitedwriter | limitedwriter | Can only write News, and not publish                                  |

# Website / MEMBERS

---

| Username | Password         | Member Group | Type                                                                    |
| -------- | ---------------- | ------------ | ----------------------------------------------------------------------- |
| premium  | premiumpremium   | Premium      | Premium, access to premium content & secret (/en/secret OR /sv/hemligt) |
| standard | standardstandard | Standard     | Standard, can't access premium or secret                                |

## G

1. Logged in user can create content according to their access level.
2. Several pages use queries to fetch content etc
3. All templates are nested under _Master
4. Articles are nested under /Articles/{Category}/{Article}

## VG

1. Dynamic menu (loads article categories)
2. 4 users declared above
3. 2 members declared above
4. Limited pages to premium (Secret @ /en/secret OR /sv/hemligt) and Premium Content (en/articles/premium/ - /sv/artiklar/premium)
5. Partial views for ArticleCard, Login, LoginStatus, RandomArticles and SignUp
6. Two available languages: English and Swedish
   1. Several dictionary entries as well as customized content
   2. Added a button to easily switch between the two to test it out


All in all, not a very great project, I got very lazy with the styling and all the functionality but as this project was more about learning about the backoffice of Umbraco rather than designing useful webpages I think I did OK. And I did learn alot about Umbraco. It's not great :D
