# Bad Seeds: Evaluating Lexical Methods for Bias Measurement

## Paper

[**Bad Seeds: Evaluating Lexical Methods for Bias Measurement**](https://maria-antoniak.github.io/resources/2021_acl_bad_seeds.pdf)  
Maria Antoniak and David Mimno  
ACL 2021

## Documentation

This repository contains the seed lexicons gathered and evaluated in the above research paper.

You can view all the gathered seeds by clicking on the `gathered_seeds.json` file above. Or you can scroll down to see the seeds in plain markdown.

You can load the seeds into a Pandas dataframe using the following Python snippet:

```
import pandas as pd
seeds_df = pd.read_json(json_path, orient='records')
```

If the seed list is empty, this means that we were unable to find a documented seed list for that category and paper.

**Note:** When using these seeds, make sure to cite the original papers and give credit to the authors who curated the seed sets. Paper titles and authors are given for each set in the JSON file, and we've included the bibtex for each paper in `gathered_seeds.bib`.

If you'd like to add new seed sets or improve the documentation for this project, please submit a pull request or contact Maria Antoniak.


## Seed Sets

**Seeds ID:** pleasant-Caliskan_et_al_2017  
**Category:** pleasant   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [caress, freedom, health, love, peace, cheer, friend, heaven, loyal, pleasure, diamond, gentle, honest, lucky, rainbow, diploma, gift, honor, miracle, sunrise, family, happy, laughter, paradise, vacation]

**Seeds ID:** unpleasant-Caliskan_et_al_2017  
**Category:** unpleasant   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [abuse, crash, filth, murder, sickness, accident, death, grief, poison, stink, assault, disaster, hatred, pollute, tragedy, divorce, jail, poverty, ugly, cancer, kill, rotten, vomit, agony, prison]

**Seeds ID:** flowers-Caliskan_et_al_2017  
**Category:** flowers   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [aster, clover, hyacinth, marigold, poppy, azalea, crocus, iris, orchid, rose, bluebell, daffodil, lilac, pansy, tulip, buttercup, daisy, lily, peony, violet, carnation, gladiola, magnolia, petunia, zinnia]

**Seeds ID:** insects-Caliskan_et_al_2017  
**Category:** insects   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [ant, caterpillar, flea, locust, spider, bedbug, centipede, fly, maggot, tarantula, bee, cockroach, gnat, mosquito, termite, beetle, cricket, hornet, moth, wasp, blackfly, dragonfly, horsefly, roach, weevil]

**Seeds ID:** instruments-Caliskan_et_al_2017  
**Category:** instruments   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [bagpipe, cello, guitar, lute, trombone, banjo, clarinet, harmonica, mandolin, trumpet, bassoon, drum, harp, oboe, tuba, bell, fiddle, harpsichord, piano, viola, bongo, flute, horn, saxophone, violin]

**Seeds ID:** weapons-Caliskan_et_al_2017  
**Category:** weapons   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [arrow, club, gun, missile, spear, axe, dagger, harpoon, pistol, sword, blade, dynamite, hatchet, rifle, tank, bomb, firearm, knife, shotgun, teargas, cannon, grenade, mace, slingshot, whip]

**Seeds ID:** european_american_names-Caliskan_et_al_2017  
**Category:** european american names   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Adam, Harry, Josh, Roger, Alan, Frank, Justin, Ryan, Andrew, Jack, Matthew, Stephen, Brad, Greg, Paul, Jonathan, Peter, Amanda, Courtney, Heather, Melanie, Katie, Betsy, Kristin, Nancy, Stephanie, Ellen, Lauren, Colleen, Emily, Megan, Rachel]

**Seeds ID:** african_american_names-Caliskan_et_al_2017  
**Category:** african american names   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Alonzo, Jamel, Theo, Alphonse, Jerome, Leroy, Torrance, Darnell, Lamar, Lionel, Tyree, Deion, Lamont, Malik, Terrence, Tyrone, Lavon, Marcellus, Wardell, Nichelle, Shereen, Ebony, Latisha, Shaniqua, Jasmine, Tanisha, Tia, Lakisha, Latoya, Yolanda, Malika, Yvette]

**Seeds ID:** european_american_names_market_discrimination-Caliskan_et_al_2017  
**Category:** european american names market discrimination   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Todd, Neil, Geoffrey, Brett, Brendan, Greg, Matthew, Brad, Allison, Anne, Carrie, Emily, Jill, Laurie, Meredith, Sarah]

**Seeds ID:** african_american_names_market_discrimination-Caliskan_et_al_2017  
**Category:** african american names market discrimination   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Kareem, Darnell, Tyrone, Hakim, Jamal, Leroy, Jermaine, Rasheed, Aisha, Ebony, Keisha, Kenya, Lakisha, Latoya, Tamika, Tanisha]

**Seeds ID:** pleasantness-Caliskan_et_al_2017  
**Category:** pleasantness   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [joy, love, peace, wonderful, pleasure, friend, laughter, happy]

**Seeds ID:** unpleasantness-Caliskan_et_al_2017  
**Category:** unpleasantness   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [agony, terrible, horrible, nasty, evil, war, awful, failure]

**Seeds ID:** male_names_1-Caliskan_et_al_2017  
**Category:** male names 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [John, Paul, Mike, Kevin, Steve, Greg, Jeff, Bill]

**Seeds ID:** female_names_1-Caliskan_et_al_2017  
**Category:** female names 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Amy, Joan, Lisa, Sarah, Diana, Kate, Ann, Donna]

**Seeds ID:** career-Caliskan_et_al_2017  
**Category:** career   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [executive, management, professional, corporation, salary, office, business, career]

**Seeds ID:** family-Caliskan_et_al_2017  
**Category:** family   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [home, parents, children, family, cousins, marriage, wedding, relatives]

**Seeds ID:** math_1-Caliskan_et_al_2017  
**Category:** math 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [math, algebra, geometry, calculus, equations, computation, numbers, addition]

**Seeds ID:** arts_1-Caliskan_et_al_2017  
**Category:** arts 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [poetry, art, sculpture, dance, literature, novel, symphony, drama]

**Seeds ID:** male_1-Caliskan_et_al_2017  
**Category:** male 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [brother, male, man, boy, son, he, his, him]

**Seeds ID:** female_1-Caliskan_et_al_2017  
**Category:** female 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [sister, female, woman, girl, daughter, she, hers, her]

**Seeds ID:** science_1-Caliskan_et_al_2017  
**Category:** science 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [science, technology, physics, chemistry, Einstein, NASA, experiment, astronomy]

**Seeds ID:** arts_2-Caliskan_et_al_2017  
**Category:** arts 2   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [poetry, art, Shakespeare, dance, literature, novel, symphony, drama]

**Seeds ID:** male_2-Caliskan_et_al_2017  
**Category:** male 2   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [brother, father, uncle, grandfather, son, he, his, him]

**Seeds ID:** female_2-Caliskan_et_al_2017  
**Category:** female 2   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [sister, mother, aunt, grandmother, daughter, she, hers, her]

**Seeds ID:** careers-Caliskan_et_al_2017  
**Category:** careers   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** population-derived  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [technician, accountant, supervisor, engineer, worker, educator, clerk, counselor, inspector, mechanic, manager, therapist, administrator, salesperson, receptionist, librarian, advisor, pharmacist, janitor, psychologist, physician, carpenter, nurse, investigator, bartender, specialist, electrician, officer, pathologist, teacher, lawyer, planner, practitioner, plumber, instructor, surgeon, veterinarian, paramedic, examiner, chemist, machinist, appraiser, nutritionist, architect, hairdresser, baker, programmer, paralegal, hygienist, scientist]

**Seeds ID:** androgynous_names-Caliskan_et_al_2017  
**Category:** androgynous names   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:** population-derived  
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Kelly, Tracy, Jamie, Jackie, Jesse, Courtney, Lynn, Taylor, Leslie, Shannon, Stacey, Jessie, Shawn, Stacy, Casey, Bobby, Terry, Lee, Ashley, Eddie, Chris, Jody, Pat, Carey, Willie, Morgan, Robbie, Joan, Alexis, Kris, Frankie, Bobbie, Dale, Robin, Billie, Adrian, Kim, Jaime, Jean, Francis, Marion, Dana, Rene, Johnnie, Jordan, Carmen, Ollie, Dominique, Jimmie, Shelby]

**Seeds ID:** depressed_1-Caliskan_et_al_2017  
**Category:** depressed 1   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [sad, hopeless, gloomy, tearful, miserable, depressed]

**Seeds ID:** physically_ill-Caliskan_et_al_2017  
**Category:** physically ill   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [sick, illness, influenza, disease, virus, cancer]

**Seeds ID:** temporary-Caliskan_et_al_2017  
**Category:** temporary   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [impermanent, unstable, variable, fleeting, short-term, brief, occasional]

**Seeds ID:** permanent-Caliskan_et_al_2017  
**Category:** permanent   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [stable, always, constant, persistent, chronic, prolonged, forever]

**Seeds ID:** young_names-Caliskan_et_al_2017  
**Category:** young names   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Tiffany, Michelle, Cindy, Kristy, Brad, Eric, Joey, Billy]

**Seeds ID:** old_names-Caliskan_et_al_2017  
**Category:** old names   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [Ethel, Bernice, Gertrude, Agnes, Cecil, Wilbert, Mortimer, Edgar]

**Seeds ID:** pleasant_6-Caliskan_et_al_2017  
**Category:** pleasant 6   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [joy, love, peace, wonderful, pleasure, friend, laughter, happy]

**Seeds ID:** unpleasant_6-Caliskan_et_al_2017  
**Category:** unpleasant 6   
**Used in Paper:** Semantics derived automatically from language corpora contain human-like biases (Caliskan et al., 2017)  
**Source Categories:**   
**Link:** [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DX4VWP)  
**Seeds:** [agony, terrible, horrible, nasty, evil, war, awful, failure]

**Seeds ID:** definitional_female-Bolukbasi_et_al_2016  
**Category:** definitional female   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:** curated  
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [woman, girl, she, mother, daugher, gal, female, her, herself, Mary]

**Seeds ID:** definitional_male-Bolukbasi_et_al_2016  
**Category:** definitional male   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:** curated  
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [man, boy, he, father, son, guy, male, his, himself, John]

**Seeds ID:** equalize_1-Bolukbasi_et_al_2016  
**Category:** equalize 1   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [monastery, spokesman, Catholic_priest, Dad, Men, councilman, grandpa, grandsons, prostate_cancer, testosterone, uncle, wives, Father, Grandpa, He, boy, boys, brother, brothers, businessman, chairman, colt, congressman, dad, dads, dudes, ex_girlfriend, father, fatherhood, fathers, fella, fraternity, gelding, gentleman, gentlemen, grandfather, grandson, he, himself, his, king, kings, male, males, man, men, nephew, prince, schoolboy, son, sons, twin_brother]

**Seeds ID:** equalize_2-Bolukbasi_et_al_2016  
**Category:** equalize 2   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:**   
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [convent, spokeswoman, nun, Mom, Women, councilwoman, grandma, granddaughters, ovarian_cancer, estrogen, aunt, husbands, Mother, Grandma, She, girl, girls, sister, sisters, businesswoman, chairwoman, filly, congresswoman, mom, moms, gals, ex_boyfriend, mother, motherhood, mothers, granny, sorority, mare, lady, ladies, grandmother, granddaughter, she, herself, her, queen, queens, female, females, woman, women, niece, princess, schoolgirl, daughter, daughters, twin_sister]

**Seeds ID:** gender_specific-Bolukbasi_et_al_2016  
**Category:** gender specific   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:**   
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [he, his, He, her, she, him, She, man, women, men, His, woman, spokesman, wife, himself, son, mother, father, chairman, daughter, husband, guy, girls, girl, Her, boy, King, boys, brother, Chairman, spokeswoman, female, sister, Women, Man, male, herself, Lions, Lady, brothers, dad, actress, mom, sons, girlfriend, Kings, Men, daughters, Prince, Queen, teenager, lady, Bulls, boyfriend, sisters, Colts, mothers, Sir, king, businessman, Boys, grandmother, grandfather, deer, cousin, Woman, ladies, Girls, Father, uncle, PA, Boy, Councilman, mum, Brothers, MA, males, Girl, Mom, Guy, Queens, congressman, Dad, Mother, grandson, twins, bull, queen, businessmen, wives, widow, nephew, bride, females, aunt, Congressman, prostate_cancer, lesbian, chairwoman, fathers, Son, moms, Ladies, maiden, granddaughter, younger_brother, Princess, Guys, lads, Ma, Sons, lion, Bachelor, gentleman, fraternity, bachelor, niece, Lion, Sister, bulls, husbands, prince, colt, salesman, Bull, Sisters, hers, dude, Spokesman, beard, filly, Actress, Him, princess, Brother, lesbians, councilman, actresses, Viagra, gentlemen, stepfather, Deer, monks, Beard, Uncle, ex_girlfriend, lad, sperm, Daddy, testosterone, MAN, Female, nephews, maid, daddy, mare, fiance, Wife, fiancee, kings, dads, waitress, Male, maternal, heroine, feminist, Mama, nieces, girlfriends, Councilwoman, sir, stud, Mothers, mistress, lions, estranged_wife, womb, Brotherhood, Statesman, grandma, maternity, estrogen, ex_boyfriend, widows, gelding, diva, teenage_girls, nuns, Daughter, czar, ovarian_cancer, HE, Monk, countrymen, Grandma, teenage_girl, penis, bloke, nun, Husband, brides, housewife, spokesmen, suitors, menopause, monastery, patriarch, Beau, motherhood, brethren, stepmother, Dude, prostate, Moms, hostess, twin_brother, Colt, schoolboy, eldest, brotherhood, Godfather, fillies, stepson, congresswoman, Chairwoman, Daughters, uncles, witch, Mommy, monk, viagra, paternity, suitor, chick, Pa, fianc\\u00e9, sorority, macho, Spokeswoman, businesswoman, eldest_son, gal, statesman, schoolgirl, fathered, goddess, hubby, mares, stepdaughter, blokes, dudes, socialite, strongman, Witch, fianc\\u00e9e, uterus, grandsons, Bride, studs, mama, Aunt, godfather, hens, hen, mommy, Babe, estranged_husband, Fathers, elder_brother, boyhood, baritone, Diva, Lesbian, grandmothers, grandpa, boyfriends, feminism, countryman, stallion, heiress, queens, Grandpa, witches, aunts, semen, fella, granddaughters, chap, knight, widower, Maiden, salesmen, convent, KING, vagina, beau, babe, HIS, beards, handyman, twin_sister, maids, gals, housewives, Gentlemen, horsemen, Businessman, obstetrics, fatherhood, beauty_queen, councilwoman, princes, matriarch, colts, manly, ma, fraternities, Spokesmen, pa, fellas, Gentleman, councilmen, dowry, barbershop, Monks, WOMAN, fraternal, ballerina, manhood, Dads, heroines, granny, gynecologist, princesses, Goddess, yo, Granny, knights, eldest_daughter, HER, underage_girls, masculinity, Girlfriend, bro, Grandmother, grandfathers, crown_prince, Restless, paternal, Queen_Mother, Boyfriend, womens, Males, SHE, Countess, stepchildren, Belles, bachelors, matron, momma, Legs, maidens, goddesses, landlady, sisterhood, Grandfather, Fraternity, Majesty, Babes, lass, maternal_grandmother, blondes, ma, am, Womens, divorcee, Momma, fathering, Effie, Lad, womanhood, missus, Sisterhood, granddad, Mens, papa, gf, sis, Husbands, Hen, womanizer, gynecological, stepsister, Handsome, Prince_Charming, BOY, stepdad, teen_ager, GIRL, dame, Sorority, beauty_pageants, raspy, harem, maternal_grandfather, Hes, deliveryman, septuagenarian, damsel, paternal_grandmother, paramour, paternal_grandparents, Nun, DAD, mothering, shes, HE_, S, Nuns, teenage_daughters, auntie, widowed_mother, Girlfriends, FATHER, virile, COUPLE, grandmas, Hubby, nan, vixen, Joan_Crawford, stepdaughters, endometrial_cancer, stepsons, loins, Grandson, Mitchells, erections, Matron, Fella, daddies, ter, Sweetie, Dudes, Princesses, Lads, lioness, Mamma, virility, bros, womenfolk, Heir, BROTHERS, manliness, patriarchs, earl, sisterly, Whore, Gynaecology, countess, convents, Oratory, witch_doctor, mamas, yah, aunty, aunties, Heiress, lasses, Breasts, fairer_sex, sorority_sisters, WIFE, Laurels, penile, nuh, mah, toms, mam, Granddad, premenopausal_women, Granddaddy, nana, coeds, dames, herdsman, Mammy, Fellas, Niece, menfolk, Grandad, bloods, Gramps, damsels, Granddaughter, mamma, concubine, Oros, Blarney, filial, broads, Ethel_Kennedy, ACTRESS, Tit, fianc, Hunk, Night_Shift, wifey, Lothario, Holy_Roman_Emperor, horse_breeder, grandnephew, Lewises, Muscular, feminist_movement, Sanan, women\\u00e2_\\u20ac_\\u2122, Fiancee, dowries, Carmelite, rah, n_roller, bay_filly, belles, Uncles, PRINCESS, womans, Homeboy, Blokes, Charmer, codger, Delta_Zeta, courtesans, grandaughter, SISTER, Highness, grandbabies, crone, Skip_Away, noblewoman, bf, jane, philandering_husband, Sisqo, mammy, daugher, director_Skip_Bertman, DAUGHTER, Royal_Highness, mannish, spinsters, Missus, madame, Godfathers, saleswomen, beaus, Risha, luh, sah, negligee, Women\\u00e2_\\u20ac_\\u2122, Hos, salesgirl, grandmom, Grandmas, Lawsons, countrywomen, Booby, darlin, Sheiks, boyz, wifes, Bayi, Il_Duce, \\u00e2_\\u20ac_\\u0153My, fem, daugther, Potti, hussy, tch, Gelding, stemmed_roses, Damson, puh, Tylers, neice, Mutha, GRANDMOTHER, youse, spurned_lover, mae, Britt_Ekland, clotheshorse, Carlita_Kilpatrick, Cambest, Pretty_Polly, banshees, male_chauvinist, Arliss, mommas, maidservant, Gale_Harold, Little_Bo_Peep, Cleavers, hags, blowsy, Queen_Elizabeth_I., lassies, papas, BABE, ugly_ducklings, Jims, hellion, Beautician, coalminer, relaxin, El_Mahroug, Victoria_Secret_Angel, shepherdess, Mosco, Slacks, nanna, wifely, tomboys, LAH, hast, apo, Kaplans, milkmaid, Robin_Munis, John_Barleycorn, royal_highness, Meanie, NAH, trollop, roh, Jewess, Sheik_Hamad, mumsy, Big_Pussy, chil_dren, Aunt_Bea, basso, sista, girlies, nun_Sister, chica, Bubbas, massa, Southern_belles, Nephews, castrations, Mister_Ed, Grandsons, Calaf, Malachy_McCourt, Shamash, hey_hey, Harmen, sonofabitch, Donovans, Grannie, Kalinka, hisself, Devean, goatherd, hinds, El_Corredor, Kens, notorious_womanizer, goh, Mommas, washerwoman, Samaira, Coo_Coo, Governess, grandsire, PRINCE_WILLIAM, gramma, him.He, Coptic_priest, Corbie, Kennys, thathe, Pa_Pa, Bristols, Hotep, snowy_haired, El_Prado_Ire, Girl_hitmaker, Hurleys, St._Meinrad, sexually_perverted, authoress, Prudie, raven_haired_beauty, Bonos, domestic_shorthair, brothas, nymphet, Neelma, Seita, stud_muffin, St._Judes, yenta, bare_shouldered, Pinkney_Sr., PRINCE_CHARLES, Bisutti, sistas, Blanche_Devereaux, Momoa, Quiff, Scotswoman, balaclava_clad_men, Louis_Leakey, dearie, vacuum_cleaner_salesman, grandads, postulant, SARAH_JESSICA_PARKER, AUNT, Prince_Dauntless, Dalys, Darkie, Czar_Nicholas, Lion_Hearted, Boy_recliner, baby_mamas, giantess, Lawd, GRANNY, fianc_e, Bilqis, WCTU, famly, Ellas, feminazis, Pentheus, MAMAS, Town_Criers, Saggy, youngman, grandam, divorc\\u00e9, bosomed, roon, Simmentals, eponymous_heroine, LEYLAND, REE, cain, t, Evelynn, WAH, sistah, Horners, Elsie_Poncher, Coochie, rat_terriers, Limousins, Buchinski, Schicchi, Carpitcher, Khwezi, HAH, Shazza, Mackeson, ROH, kuya, novice_nun, Shei, Elmasri, ladykiller, 6yo, Yenta, SHEL, pater, Souse, Tahirah, comedian_Rodney_Dangerfield, Shottle, carryin, Sath, fa, afafine, royal_consort, hus_band, maternal_uncles, dressing_provocatively, dreamgirl, millionaire_industrialist, Georgie_Girl, Must_Be_Obeyed, joh, Arabian_stallion, ahr, mso_para_margin_0in, SOO, Biddles, Chincoteague_Volunteer_Fire, Lisa_Miceli, gorgeous_brunette, fianc\\u017d, Moved_fluently, Afternoon_Deelites, biker_dude, Vito_Spatafore, MICK_JAGGER, Adesida, Reineman, witz, Djamila, Glenroe, daddys, Romanzi, gentlewomen, Dandie_Dinmont_terrier, Excess_Ire, By_SYVJ_Staff, zan, CONFESSIONS, Magees, wimmin, tash, Theatrical_Ire, Prince_Charmings, chocolate_eclair, bron, daughers, Felly, fiftyish, Spritely, GRANDPA, distaffer, Norbertines, DAH, leader_Muammar_Gadaffi, swains, Prince_Tomohito, Honneur, Soeur, jouster, Pharaoh_Amenhotep_III, QUEEN_ELIZABETH_II, Ne, er, Galileo_Ire, Fools_Crow, Lannisters, Devines, gonzales, columnist_Ann_Landers, Moseleys, hiz, busch, roastee, toyboys, Sheffields, grandaunt, Galvins, Giongo, geh, flame_haired_actress, Grammarian, Greg_Evigan, frontierswoman, Debele, rabs, nymphets, aai, BREE, Shaqs, ZAY, pappa, Housa, refrigerator_repairman, artificial_inseminations, chickie, Rippa, teenager_Tracy_Turnblad, homebred_colt, Abigaille, hen_pecked_husband, businesman, her.She, Kaikeyi, Stittsworth, self_proclaimed_redneck, Khella, NeW, Evers_Swindell, Asmerom_Gebreselassie, Boy_recliners, Cliff_Claven, Legge_Bourke, Costos, d, _honneur, sistahs, Cabble, sahn, CROW_AGENCY_Mont, jezebel, Harrolds, ROSARIO_DAWSON, INXS_frontman_Michael_Hutchence, Gursikh, Dadas, VIAGA, keen_horsewoman, Theodoric, Eldery, lihn, Alice_Kramden, Santarina, radical_cleric_al_Sadr, Curleys, SY, Fidaa, Saptapadi, Actor_Sean_Astin, Kellita_Smith, Doly, Libertina, Money_McBags, Chief_Bearhart, choirgirl, chestnut_stallion, VIGRA, BY_JIM_McCONNELL, Sal_Vitale, Trivia_buffs, kumaris, fraternal_lodge, galpals, Borino_Quinn, lina, LATEST_Rapper, Bezar, Manro, bakla, Grisetti, blond_bimbo, spinster_aunt, gurls, hiswife, paleface, Charlye, hippie_chicks, Khalifas, Picture_JUSTIN_SANSON, Hepburns, yez, ALDER, Sanussi, Lil_Sis, McLoughlins, Barbra_Jean, Lulua, thatshe, actress_Shohreh_Aghdashloo, SIR_ANTHONY_HOPKINS, Gloddy, ZAH, ORANGE_, S, Danielle_Bimber, grandmum, Kulkis, Brazington, Marisa_Lenhard_CFA, SIR_JOHN, Clareman, Aqila, Heavily_tattooed, Libbys, thim, elocutionist, submissives, Inja, rahm, Agnes_Gooch, fake_tits, nancy_boys, Swaidan, SHAH, ain, ta_bed, Shumail_Raj, Duchesse, diethylstilbestrol_DES, colt_foal, unfaithful_lover, Maseri, nevah, SAHN, Barths, Toughkenamon, GUEST_STARS, him.But, Donna_Claspell, gingham_dresses, Massage_Parlour, wae, Wasacz, Magistra, vihl, Smriti_Iraani, boyish_haircut, workingwoman, borthers, Capuchin_friars, Nejma, yes_sirs, bivocational_pastor, Grafters, HOPWOOD, Nicknamed_Godzilla, yos, Berkenfield, Missis, sitcom_Designing_Women, Kafoa, trainer_Emma_Lavelle, sadomasochistic_dungeon, iht, desperates, predessor, wolf_cub, indigenous_Peruvians, Livia_Soprano, troh, colt_sired, BOND_HILL, ihl, Drydens, rahs, Piserchia, Sonny_Corinthos, bankrobber, Fwank, feisty_redhead, booze_guzzling, COOPERS, actress_Q, orianka_Kilcher, Cortezar, twe, Jacoub, Cindy_Iannarelli, Hell_Raiser, Fondly_referred, Bridal_Shoppe, Noleta, Christinas, IAGRA, LaTanya_Richardson, Sang_Bender, Assasins, sorrel_gelding, septugenarian, Hissy, Muqtada_al_Sadr_mook, Pfeni, MADRID_AFX_Banco_Santander, tuchis, LeVaughn, Gadzicki, transvestite_hooker, Fame_jockey_Laffit, nun_Sister_Mary, SAMSONOV, Mayflower_Madam, Shaque, well.He, Trainer_Julio_Canani, sorrel_mare, minivehicle_joint_venture, wife_Dwina, Aasiya_AH, _see, Baratheon, Rick_O, Shay, Mammies, goatie, Nell_Gwynne, charmingly_awkward, Slamma, DEHL, Lorenzo_Borghese, ALMA_Wis., Anne_Scurria, father_Peruvians_alternately, JULIE_ANDREWS, Slim_Pickins, Victoria_Secret_stunner, BY, Sanam_Devdas, pronounced_luh, Pasha_Selim, \\u4e2d\\u534e, rson, maternal_grandmothers, IOWA_CITY_Ia, Madame_de_Tourvel, JAY, Sheika_Mozah_bint_Nasser, Hotsy_Totsy, D, _Ginto, singer_Johnny_Paycheck, uterine_prolapse_surgery, SCOTTDALE_Pa., AdelaideNow_reports, Marcus_Schenkenberg, Clyse, Obiter_Dicta, comic_Sam_Kinison, bitties, ROCKVILLE_Ind., swimsuit_calendars, Decicio_Smith, Ma_ma, Rie_Miyazawa, celibate_chastity, gwah, ZAY, HER_Majesty, Defrere, Las_Madrinas, \\u7c3f_\\u8042_\\u7ffb, Bea_Hamill, ARCADIA_Calif._Trainer, Bold_Badgett, stakes_victress, Hoppin_Frog, Narumiya, Flayfil, hardman_Vinnie_Jones, Marilyn_Monroe_lookalike, Kivanc_Tatlitug, Persis_Khambatta, SINKING_SPRING_Pa., len_3rd, DEAR_TRYING, Farndon_Cheshire, Krishna_Madiga, daughter_Princess_Chulabhorn, Marshall_Rooster_Cogburn, Kitty_Kiernan, Yokich, Jarou, Serdaris, ee_ay, Montifiore, Chuderewicz, Samuel_Le_Bihan, filly_Proud_Spell, Umm_Hiba, pronounced_koo, Sandy_Fonzo, KOR, Fielder_Civil_kisses, Federalsburg_Maryland, Nikah_ceremony, Brinke_Stevens, Yakama_Tribal_Council, Capuchin_Father, wife_Callista_Bisek, Beau_Dare, Bedoni, Arjun_Punj, JOHNNY_KNOXVILLE, cap_tain, Alderwood_Boys, Chi_Eta_Phi, ringleader_Charles_Graner, Savoies, Lalla_Salma, Mrs._Potiphar, fahn, name_Taylor_Sumers, Vernita_Green, Bollywood_baddie, BENBROOK_Texas, Assemblyman_Lou_Papan, virgin_brides, Cho_Eun, CATHY_Freeman, Uncle_Saul, Lao_Brewery, Ibo_tribe, ruf, rival_Edurne_Pasaban, Hei_Shangri_La, Mommy_dearest, interest_Angola_Sonogal, Ger_Monsun, PUSSYCAT_DOLL, Crown_Jewels_Condoms, Lord_Marke, Patootie, Nora_Bey, huntin_shootin, Minister_Raymond_Tshibanda, La_Nina_la_NEEN, signature_Whoppers, estranged_hubby_Kevin_Federline, UR, pill_poppin, GEHR, purebred_Arabians, husbandly_duties, VIAGRA_TIMING, Hereford_heifer, hushed_monotone_voice, Pola_Uddin, Wee_Jimmy_Krankie, Kwakwanso, Our_Galvinator, shoh, Codependency_Anonymous_Group, LA, Taufa, ahau, Invincible_Spirit_colt, SAH, _dur, MOUNT_CARMEL_Pa., watches_attentively, SNL_spinoffs, Seth_Nitschke, Duns_Berwickshire, defendant_Colleen_LaRose, Silky_O, Sullivan, Highcliff_Farm, REN, Comestar, Satisfied_Frog, Jai_Maharashtra, ATTICA_Ind., lover_Larry_Birkhead, Tami_Megal, chauvinist_pigs, Phi_sorority, Micronesian_immigrant, Lia_Boldt, Sugar_Tits, actress_Kathy_Najimy, zhoo, Colombo_underboss, Katsav_accusers, Bess_Houdini, rap_mogul_Diddy, companions_Khin_Khin, Van_Het, Mastoi_tribe, VITALY, ROLLING_STONES_rocker, womanizing_cad, LILY_COLE, paternal_grandfathers, Lt._Col._Kurt_Kosmatka, Kasseem_Jr., Ji_Ji, Wilburforce, VIAGRA_DOSE, English_Sheepdogs, pronounced_Kah, Htet_Htet_Oo, Brisk_Breeze, Eau_du, BY_MELANIE_EVANS, Neovasc_Medical, British_funnyman_RICKY, 4YO_mare, Hemaida, MONKTON, Mrs_Mujuru, BaGhana_BaGhana, Shaaban_Abdel_Rahim, Edward_Jazlowiecki_lawyer, Ajman_Stud, manly_pharaoh_even, Serra_Madeira_Islands, FRAY, panto_dames, Khin_Myo, dancer_Karima_El_Mahroug, CROWN_Princess, Baseball_HOFer, Hasta_la_Pasta, GIRLS_NEXT_DOOR, Benedict_Groeschel, Bousamra, Ruby_Rubacuori_Ruby, Monde_Bleu, Un_homme_qui, Taylor_Sumers, Rapper_EMINEM, Joe_Menchetti, VAY, supermodel_NAOMI_CAMPBELL, Supermodel_GISELE_BUNDCHEN, Au_Lait, Radar_Installed, THOMAS_TOWNSHIP_Mich., Rafinesque, Herman_Weinrich, Abraxas_Antelope, raspy_voiced_rocker, Manurewa_Cosmopolitan_Club, Paraone, THE_LEOPARD, Boy_Incorporated_LZB, Dansili_filly, Lumpy_Rutherford, unwedded_bliss, Bhavna_Sharma, Scarvagh, en_flagrante, Mottu_Maid, Dowager_Queen, NEEN, model_Monika_Zsibrita, ROSIE_PEREZ, Mattock_Ranger, Valorous, Surpreme, Marwari_businessmen, Grandparents_aunts, Kimberley_Vlaeminck, Lyn_Treece_Boys, PDX_Update, Virsa_Punjab, eyelash_fluttering, Pi_fraternity, HUNTLEIGH_Mo., novelist_Jilly_Cooper, Naha_Shuri_temple, Yasmine_Al_Massri, Mu_Gamma_Xi, Mica_Ertegun, Ocleppo, VIAGRA_CONTRAINDICATIONS, daughter_PEACHES, trainer_Geoff_Wragg, OVERNIGHT_DELIVERY, Fitts_retiree, de_Tourvel, Lil_Lad, north_easterner, Aol_Weird_News, Somewhat_improbably, Sikh_panth, Worcester_2m_7f, Zainab_Jah, OLYMPIC_medalist, Enoch_Petrucelly, collie_Lassie, LOW, clumsiness_Holloway, ayr, OHR, ROLLING_STONES_guitarist, LAH, _nee, Ian_Beefy_Botham, Awapuni_trainer, Glamorous_Granny, Chiang_Ching, MidAtlantic_Cardiovascular_Associates, Yeke, Seaforth_Huron_Expositor, Westley_Cary_Elwes, Cate_Blanchett_Veronica_Guerin, Bellas_Gate, witch_Glinda, wives_mistresses, Woodsville_Walmart, 2YO_colt, Manav_Sushant_Singh, Pupi_Avati_Il, Sigma_Beta_Rho, Bishop_Christopher_Senyonjo, Vodou_priest, Rubel_Chowdhury, Claddagh_Ring, TAH, _duh_al, al_Sadr_mook_TAH, ROBIN_GIBB, GAHN, BY_THOMAS_RANSON, sister_Carine_Jena, Lyphard_mare, summa_cum, Semenya_grandmother_Maputhi, Clare_Nuns, Talac, sex_hormones_androgens, majeste, Saint_Ballado_mare, Carrie_Huchel, Mae_Dok, wife_Dieula, Earnest_Sirls, spoof_bar_mitzvah, von_Boetticher, Audwin_Mosby, Case_presentationWe, Vincent_Papandrea, KRAY, Sergi_Benavent, Le_Poisson, Von_Cramm, Patti_Mell, Raymi_Coya, Benjamin_BeBe_Winans, Nana_Akosua, Auld_Acquaintance, Desire_Burunga, Company_Wrangler_Nestea, ask_Krisy_Plourde, JUANITA_BYNUM, livia, GAMB, Gail_Rosario_Dawson, Ramgarhia_Sikh, Catholic_nun_Sister, FOUR_WEDDINGS_AND, Robyn_Scherer, brother_King_Athelstan, Santo_Loquasto_Fences, Wee_Frees, MARISOL, Soliloquy_Stakes, Whatever_Spoetzl, Marc, Aurelio, mon_petit, Sabbar_al_Mashhadani, KAY, _lee, m_zah_MAH, BY_TAMI_ALTHOFF, hobbit_Samwise_Gamgee, Bahiya_Hariri_sister, daddy_Larry_Birkhead, Sow_Tracey_Ullman, coach_Viljo_Nousiainen, Carmen_Lebbos, conjoined_twins_Zainab, Rob_Komosa, ample_bosomed, Ageing_rocker, psychic_Oda]

**Seeds ID:** gender_specific_seed-Bolukbasi_et_al_2016  
**Category:** gender specific seed   
**Used in Paper:** Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings (Bolukbasi et al., 2016)  
**Source Categories:**   
**Link:** [https://github.com/tolga-b/debiaswe](https://github.com/tolga-b/debiaswe)  
**Seeds:** [actress, actresses, aunt, aunts, bachelor, ballerina, barbershop, baritone, beard, beards, beau, bloke, blokes, boy, boyfriend, boyfriends, boyhood, boys, brethren, bride, brides, brother, brotherhood, brothers, bull, bulls, businessman, businessmen, businesswoman, chairman, chairwoman, chap, colt, colts, congressman, congresswoman, convent, councilman, councilmen, councilwoman, countryman, countrymen, czar, dad, daddy, dads, daughter, daughters, deer, diva, dowry, dude, dudes, elder_brother, eldest_son, estranged_husband, estranged_wife, estrogen, ex_boyfriend, ex_girlfriend, father, fathered, fatherhood, fathers, fella, fellas, female, females, feminism, fiance, fiancee, fillies, filly, fraternal, fraternities, fraternity, gal, gals, gelding, gentleman, gentlemen, girl, girlfriend, girlfriends, girls, goddess, godfather, granddaughter, granddaughters, grandfather, grandma, grandmother, grandmothers, grandpa, grandson, grandsons, guy, handyman, he, heiress, hen, hens, her, heroine, hers, herself, him, himself, his, horsemen, hostess, housewife, housewives, hubby, husband, husbands, king, kings, lad, ladies, lads, lady, lesbian, lesbians, lion, lions, ma, macho, maid, maiden, maids, male, males, mama, man, mare, maternal, maternity, matriarch, men, menopause, mistress, mom, mommy, moms, monastery, monk, monks, mother, motherhood, mothers, nephew, nephews, niece, nieces, nun, nuns, obstetrics, ovarian_cancer, pa, paternity, penis, prince, princes, princess, prostate, prostate_cancer, queen, queens, salesman, salesmen, schoolboy, schoolgirl, semen, she, sir, sister, sisters, son, sons, sorority, sperm, spokesman, spokesmen, spokeswoman, stallion, statesman, stepdaughter, stepfather, stepmother, stepson, strongman, stud, studs, suitor, suitors, teenage_girl, teenage_girls, testosterone, twin_brother, twin_sister, uncle, uncles, uterus, vagina, viagra, waitress, widow, widower, widows, wife, witch, witches, wives, woman, womb, women, younger_brother]

**Seeds ID:** male-Manzini_et_al_2019  
**Category:** male   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [he, his, son, father, male, boy, uncle]

**Seeds ID:** female-Manzini_et_al_2019  
**Category:** female   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [she, hers, daughter, mother, female, girl, aunt]

**Seeds ID:** male_roles-Manzini_et_al_2019  
**Category:** male roles   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [manager, executive, doctor, lawyer, programmer, scientist, soldier, supervisor, rancher, janitor, firefighter, officer]

**Seeds ID:** female_roles-Manzini_et_al_2019  
**Category:** female roles   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [secretary, nurse, clerk, artist, homemaker, dancer, singer, librarian, maid, hairdresser, stylist, receptionist, counselor]

**Seeds ID:** gender_test_terms-Manzini_et_al_2019  
**Category:** gender test terms   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [chair, house, supervisor, secretary, loud, weak]

**Seeds ID:** black-Manzini_et_al_2019  
**Category:** black   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [black, african, black, africa, africa, africa]

**Seeds ID:** caucasian-Manzini_et_al_2019  
**Category:** caucasian   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [caucasian, caucasian, white, america, america, europe]

**Seeds ID:** asian-Manzini_et_al_2019  
**Category:** asian   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [asian, asian, asian, asia, china, asia]

**Seeds ID:** black_roles-Manzini_et_al_2019  
**Category:** black roles   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [slave, musician, runner, criminal, homeless]

**Seeds ID:** caucasian_roles-Manzini_et_al_2019  
**Category:** caucasian roles   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [manager, executive, redneck, hillbilly, leader, farmer]

**Seeds ID:** asian_roles-Manzini_et_al_2019  
**Category:** asian roles   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [doctor, engineer, laborer, teacher]

**Seeds ID:** race_test_terms-Manzini_et_al_2019  
**Category:** race test terms   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [chair, house, smart, criminal, executive, farmer]

**Seeds ID:** jew-Manzini_et_al_2019  
**Category:** jew   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [judaism, jew, synagogue, torah, rabbi]

**Seeds ID:** christian-Manzini_et_al_2019  
**Category:** christian   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [christianity, christian, church, bible, priest]

**Seeds ID:** muslim-Manzini_et_al_2019  
**Category:** muslim   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [islam, muslim, mosque, quran, imam]

**Seeds ID:** jewish_attributes-Manzini_et_al_2019  
**Category:** jewish attributes   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [greedy, cheap, hairy, liberal]

**Seeds ID:** christian_attributes-Manzini_et_al_2019  
**Category:** christian attributes   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [judgemental, conservative, familial]

**Seeds ID:** muslim_attributes-Manzini_et_al_2019  
**Category:** muslim attributes   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [violent, terrorist, dirty, uneducated]

**Seeds ID:** religion_test_terms-Manzini_et_al_2019  
**Category:** religion test terms   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [chair, house, greedy, terrorist, dirty, greedy]

**Seeds ID:** religion_specific_terms-Manzini_et_al_2019  
**Category:** religion specific terms   
**Used in Paper:** Black is to Criminal as Caucasian is to Police: Detecting and Removing Multiclass Bias in Word Embeddings (Manzini et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/TManzini/DebiasMulticlassWordEmbedding](https://github.com/TManzini/DebiasMulticlassWordEmbedding)  
**Seeds:** [synagogue, synagogues, altar, altars, parish, parishes, biblical, bishop, bishops, jihadist, clergy, bible, bibles, mosque, mosques, mullah, church, churches, sermon, sermons, papacy, imam, pew, chancel, pope, priest, priests, baptism, jihad, confessional, holy_eucharist, evangelical, jesus, burqa, vicar, vicars, judaism, christianity, islam, jew, christian, muslim, torah, quran, rabbi]

**Seeds ID:** adjectives_appearance-Garg_et_al_2018  
**Category:** adjectives appearance   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** other  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [alluring, voluptuous, blushing, homely, plump, sensual, gorgeous, slim, bald, athletic, fashionable, stout, ugly, muscular, slender, feeble, handsome, healthy, attractive, fat, weak, thin, pretty, beautiful, strong]

**Seeds ID:** adjectives_intelligence-Garg_et_al_2018  
**Category:** adjectives intelligence   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** other  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [precocious, resourceful, inquisitive, sagacious, inventive, astute, adaptable, reflective, discerning, intuitive, inquiring, judicious, analytical, luminous, venerable, imaginative, shrewd, thoughtful, sage, smart, ingenious, clever, brilliant, logical, intelligent, apt, genius, wise]

**Seeds ID:** adjectives_otherization-Garg_et_al_2018  
**Category:** adjectives otherization   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [devious, bizarre, venomous, erratic, barbaric, frightening, deceitful, forceful, deceptive, envious, greedy, hateful, contemptible, brutal, monstrous, calculating, cruel, intolerant, aggressive, monstrous]

**Seeds ID:** adjectives_princeton-Garg_et_al_2018  
**Category:** adjectives princeton   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [brilliant, intelligent, honest, alert, imaginative, artistic, industrious, kind, faithful, sportsmanlike, efficient, courteous, generous, ambitious, witty, individualistic, sensitive, progressive, straightforward, jovial, musical, neat, persistent, practical, scientific, sophisticated, meditative, loyal, pleasureloving, suave, happy-go-lucky, passionate, sensual, stolid, gregarious, traditional, methodical, religious, quiet, aggressive, shrewd, reserved, nationalistic, conservative, talkative, impulsive, ponderous, conventional, materialistic, radical, argumentative, frivolous, suggestible, sly, stubborn, imitative, naive, pugnacious, suspicious, evasive, loud, superstitious, mercenary, ostentatious, quicktempered, humorless, grasping, boastful, quarrelsome, gluttonous, slovenly, revengeful, arrogant, ignorant, dirty, conceited, stupid, cowardly, unreliable, treacherous, rude, deceitful, cruel]

**Seeds ID:** adjectives_sensitive-Garg_et_al_2018  
**Category:** adjectives sensitive   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [inhibited, complacent, sensitive, mellow, solemn, studious, intelligent, brilliant, rational, serious, contemplative, cowardly, timid, shy, passive, delicate, gentle, soft, quiet, working]

**Seeds ID:** adjectives_williams_best-Garg_et_al_2018  
**Category:** adjectives williams best   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [headstrong, thankless, tactful, distrustful, quarrelsome, effeminate, fickle, talkative, dependable, resentful, sarcastic, unassuming, changeable, resourceful, persevering, forgiving, assertive, individualistic, vindictive, sophisticated, deceitful, impulsive, sociable, methodical, idealistic, thrifty, outgoing, intolerant, autocratic, conceited, inventive, dreamy, appreciative, forgetful, forceful, submissive, pessimistic, versatile, adaptable, reflective, inhibited, outspoken, quitting, unselfish, immature, painstaking, leisurely, infantile, sly, praising, cynical, irresponsible, arrogant, obliging, unkind, wary, greedy, obnoxious, irritable, discreet, frivolous, cowardly, rebellious, adventurous, enterprising, unscrupulous, poised, moody, unfriendly, optimistic, disorderly, peaceable, considerate, humorous, worrying, preoccupied, trusting, mischievous, robust, superstitious, noisy, tolerant, realistic, masculine, witty, informal, prejudiced, reckless, jolly, courageous, meek, stubborn, aloof, sentimental, complaining, unaffected, cooperative, unstable, feminine, timid, retiring, relaxed, imaginative, shrewd, conscientious, industrious, hasty, commonplace, lazy, gloomy, thoughtful, dignified, wholesome, affectionate, aggressive, awkward, energetic, tough, shy, queer, careless, restless, cautious, polished, tense, suspicious, dissatisfied, ingenious, fearful, daring, persistent, demanding, impatient, contented, selfish, rude, spontaneous, conventional, cheerful, enthusiastic, modest, ambitious, alert, defensive, mature, coarse, charming, clever, shallow, deliberate, stern, emotional, rigid, mild, cruel, artistic, hurried, sympathetic, dull, civilized, loyal, withdrawn, confident, indifferent, conservative, foolish, moderate, handsome, helpful, gentle, dominant, hostile, generous, reliable, sincere, precise, calm, healthy, attractive, progressive, confused, rational, stable, bitter, sensitive, initiative, loud, thorough, logical, intelligent, steady, formal, complicated, cool, curious, reserved, silent, honest, quick, friendly, efficient, pleasant, severe, peculiar, quiet, weak, anxious, nervous, warm, slow, dependent, wise, organized, affected, reasonable, capable, active, independent, patient, practical, serious, understanding, cold, responsible, simple, original, strong, determined, natural, kind]

**Seeds ID:** female_pairs-Garg_et_al_2018  
**Category:** female pairs   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** curated  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [she, daughter, hers, her, mother, woman, girl, herself, female, sister, daughters, mothers, women, girls, females, sisters, aunt, aunts, niece, nieces]

**Seeds ID:** male_pairs-Garg_et_al_2018  
**Category:** male pairs   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** curated  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [he, son, his, him, father, man, boy, himself, male, brother, sons, fathers, men, boys, males, brothers, uncle, uncles, nephew, nephews]

**Seeds ID:** names_asian-Garg_et_al_2018  
**Category:** names asian   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [cho, wong, tang, huang, chu, chung, ng, wu, liu, chen, lin, yang, kim, chang, shah, wang, li, khan, singh, hong]

**Seeds ID:** names_black-Garg_et_al_2018  
**Category:** names black   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [harris, robinson, howard, thompson, moore, wright, anderson, clark, jackson, taylor, scott, davis, allen, adams, lewis, williams, jones, wilson, martin, johnson]

**Seeds ID:** names_chinese-Garg_et_al_2018  
**Category:** names chinese   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [chung, liu, wong, huang, ng, hu, chu, chen, lin, liang, wang, wu, yang, tang, chang, hong, li]

**Seeds ID:** names_hispanic-Garg_et_al_2018  
**Category:** names hispanic   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [ruiz, alvarez, vargas, castillo, gomez, soto, gonzalez, sanchez, rivera, mendoza, martinez, torres, rodriguez, perez, lopez, medina, diaz, garcia, castro, cruz]

**Seeds ID:** names_russian-Garg_et_al_2018  
**Category:** names russian   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [gurin, minsky, sokolov, markov, maslow, novikoff, mishkin, smirnov, orloff, ivanov, sokoloff, davidoff, savin, romanoff, babinski, sorokin, levin, pavlov, rodin, agin]

**Seeds ID:** names_white-Garg_et_al_2018  
**Category:** names white   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** corpus-derived, population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [harris, nelson, robinson, thompson, moore, wright, anderson, clark, jackson, taylor, scott, davis, allen, adams, lewis, williams, jones, wilson, martin, johnson]

**Seeds ID:** occuptations_1950_professional-Garg_et_al_2018  
**Category:** occupations   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** population-derived  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [janitor, statistician, midwife, bailiff, auctioneer, photographer, geologist, shoemaker, athlete, cashier, dancer, housekeeper, accountant, physicist, gardener, dentist, weaver, blacksmith, psychologist, supervisor, mathematician, surveyor, tailor, designer, economist, mechanic, laborer, postmaster, broker, chemist, librarian, attendant, clerical, musician, porter, scientist, carpenter, sailor, instructor, sheriff, pilot, inspector, mason, baker, administrator, architect, collector, operator, surgeon, driver, painter, conductor, nurse, cook, engineer, retired, sales, lawyer, clergy, physician, farmer, clerk, manager, guard, artist, smith, official, police, doctor, professor, student, judge, teacher, author, secretary, soldier]

**Seeds ID:** occupations_1950-Garg_et_al_2018  
**Category:** occupations professional   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** curated  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [statistician, auctioneer, photographer, geologist, accountant, physicist, dentist, psychologist, supervisor, mathematician, designer, economist, postmaster, broker, chemist, librarian, scientist, instructor, pilot, administrator, architect, surgeon, nurse, engineer, lawyer, physician, manager, official, doctor, professor, student, judge, teacher, author]

**Seeds ID:** occupations_mechanical_turk-Garg_et_al_2018  
**Category:** occupations mechanical turk   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** prior-work  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [instructor, geologist, secretary, clerk, painter, housekeeper, chemist, artist, baker, psychologist, lawyer, teacher, collector, surveyor, accountant, sailor, laborer, physician, student, soldier, manager, administrator, musician, doctor, dentist, professor, photographer, surgeon, inspector, janitor, nurse, author, conductor, economist, physicist, scientist, architect, mechanic, judge, gardener, farmer, librarian, carpenter, mathematician, dancer, broker, athlete]

**Seeds ID:** personality_traits_original-Garg_et_al_2018  
**Category:** personality traits original   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [disorganized, devious, impressionable, circumspect, impassive, aimless, effeminate, unfathomable, fickle, unprincipled, inoffensive, reactive, providential, resentful, bizarre, impractical, sarcastic, misguided, imitative, pedantic, venomous, erratic, insecure, resourceful, neurotic, forgiving, profligate, whimsical, assertive, incorruptible, individualistic, faithless, disconcerting, barbaric, hypnotic, vindictive, observant, dissolute, frightening, complacent, boisterous, pretentious, disobedient, tasteless, sedentary, sophisticated, regimental, mellow, deceitful, impulsive, playful, sociable, methodical, willful, idealistic, boyish, callous, pompous, unchanging, crafty, punctual, compassionate, intolerant, challenging, scornful, possessive, conceited, imprudent, dutiful, lovable, disloyal, dreamy, appreciative, forgetful, unrestrained, forceful, submissive, predatory, fanatical, illogical, tidy, aspiring, studious, adaptable, conciliatory, artful, thoughtless, deceptive, frugal, reflective, insulting, unreliable, stoic, hysterical, rustic, inhibited, outspoken, unhealthy, ascetic, skeptical, painstaking, contemplative, leisurely, sly, mannered, outrageous, lyrical, placid, cynical, irresponsible, vulnerable, arrogant, persuasive, perverse, steadfast, crisp, envious, naive, greedy, presumptuous, obnoxious, irritable, dishonest, discreet, sporting, hateful, ungrateful, frivolous, reactionary, skillful, cowardly, sordid, adventurous, dogmatic, intuitive, bland, indulgent, discontented, dominating, articulate, fanciful, discouraging, treacherous, repressed, moody, sensual, unfriendly, optimistic, clumsy, contemptible, focused, haughty, morbid, disorderly, considerate, humorous, preoccupied, airy, impersonal, cultured, trusting, respectful, scrupulous, scholarly, superstitious, tolerant, realistic, malicious, irrational, sane, colorless, masculine, witty, inert, prejudiced, fraudulent, blunt, childish, brittle, disciplined, responsive, courageous, bewildered, courteous, stubborn, aloof, sentimental, athletic, extravagant, brutal, manly, cooperative, unstable, youthful, timid, amiable, retiring, fiery, confidential, relaxed, imaginative, mystical, shrewd, conscientious, monstrous, grim, questioning, lazy, dynamic, gloomy, troublesome, abrupt, eloquent, dignified, hearty, gallant, benevolent, maternal, paternal, patriotic, aggressive, competitive, elegant, flexible, gracious, energetic, tough, contradictory, shy, careless, cautious, polished, sage, tense, caring, suspicious, sober, neat, transparent, disturbing, passionate, obedient, crazy, restrained, fearful, daring, prudent, demanding, impatient, cerebral, calculating, amusing, honorable, casual, sharing, selfish, ruined, spontaneous, admirable, conventional, cheerful, solitary, upright, stiff, enthusiastic, petty, dirty, subjective, heroic, stupid, modest, impressive, orderly, ambitious, protective, silly, alert, destructive, exciting, crude, ridiculous, subtle, mature, creative, coarse, passive, oppressed, accessible, charming, clever, decent, miserable, superficial, shallow, stern, winning, balanced, emotional, rigid, invisible, desperate, cruel, romantic, agreeable, hurried, sympathetic, solemn, systematic, vague, peaceful, humble, dull, expedient, loyal, decisive, arbitrary, earnest, confident, conservative, foolish, moderate, helpful, delicate, gentle, dedicated, hostile, generous, reliable, dramatic, precise, calm, healthy, attractive, artificial, progressive, odd, confused, rational, brilliant, intense, genuine, mistaken, driving, stable, objective, sensitive, neutral, strict, angry, profound, smooth, ignorant, thorough, logical, intelligent, extraordinary, experimental, steady, formal, faithful, curious, reserved, honest, busy, educated, liberal, friendly, efficient, sweet, surprising, mechanical, clean, critical, criminal, soft, proud, quiet, weak, anxious, solid, complex, grand, warm, slow, false, extreme, narrow, dependent, wise, organized, pure, directed, dry, obvious, popular, capable, secure, active, independent, ordinary, fixed, practical, serious, fair, understanding, constant, cold, responsible, deep, religious, private, simple, physical, original, working, strong, modern, determined, open, political, difficult, knowledge, kind]

**Seeds ID:** christianity-Garg_et_al_2018  
**Category:** christianity   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** unknown  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [baptism, messiah, catholicism, resurrection, christianity, salvation, protestant, gospel, trinity, jesus, christ, christian, cross, catholic, church]

**Seeds ID:** islam-Garg_et_al_2018  
**Category:** islam   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** unknown  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [allah, ramadan, turban, emir, salaam, sunni, koran, imam, sultan, prophet, veil, ayatollah, shiite, mosque, islam, sheik, muslim, muhammad]

**Seeds ID:** terrorism-Garg_et_al_2018  
**Category:** terrorism   
**Used in Paper:** Word Embeddings Quantify 100 Years of Gender and Ethnic Stereotypes (Garg et al., 2018)  
**Source Categories:** unknown  
**Link:** [https://github.com/nikhgarg/EmbeddingDynamicStereotypes](https://github.com/nikhgarg/EmbeddingDynamicStereotypes)  
**Seeds:** [terror, terrorism, violence, attack, death, military, war, radical, injuries, bomb, target, conflict, dangerous, kill, murder, strike, dead, violence, fight, death, force, stronghold, wreckage, aggression, slaughter, execute, overthrow, casualties, massacre, retaliation, proliferation, militia, hostility, debris, acid, execution, militant, rocket, guerrilla, sacrifice, enemy, soldier, terrorist, missile, hostile, revolution, resistance, shoot]

**Seeds ID:** occupations-Kozlowski_et_al_2019  
**Category:** occupations   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [banker, carpenter, doctor, engineer, hairdresser, journalist, lawyer, nanny, nurse, plumber, scientist]

**Seeds ID:** clothing-Kozlowski_et_al_2019  
**Category:** clothing   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [blouse, briefcase, dress, necklace, pants, shirt, shorts, socks, suit, tuxedo]

**Seeds ID:** sports-Kozlowski_et_al_2019  
**Category:** sports   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [baseball, basketball, boxing, golf, hockey, soccer, softball, tennis, volleyball]

**Seeds ID:** music_genres-Kozlowski_et_al_2019  
**Category:** music genres   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [bluegrass, hiphop, jazz, opera, punk, rap, techno]

**Seeds ID:** vehicles-Kozlowski_et_al_2019  
**Category:** vehicles   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [bicycle, limousine, minivan, motorcycle, skateboard, suv, truck]

**Seeds ID:** food-Kozlowski_et_al_2019  
**Category:** food   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [beer, cheesecake, hamburger, pastry, salad, steak]

**Seeds ID:** first_names-Kozlowski_et_al_2019  
**Category:** first names   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** crowd-sourced, curated  
**Link:** []()  
**Seeds:** [Aaliyah, Amy, Connor, Jake, Jamal, Molly, Shanice]

**Seeds ID:** male-Kozlowski_et_al_2019  
**Category:** male   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [man, men, he, him, his, his, boy, boys, male, masculine]

**Seeds ID:** female-Kozlowski_et_al_2019  
**Category:** female   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [woman, women, she, her, her, hers, girl, girls, female, feminine]

**Seeds ID:** upperclass-Kozlowski_et_al_2019  
**Category:** upperclass   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [rich, richer, richest, affluence, affluent, expensive, luxury, opulent]

**Seeds ID:** lowerclass-Kozlowski_et_al_2019  
**Category:** lowerclass   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [poor, poorer, poorest, poverty, impoverished, inexpensive, cheap, needy]

**Seeds ID:** black-Kozlowski_et_al_2019  
**Category:** black   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [black, blacks, Blacks, Black, African, African]

**Seeds ID:** white-Kozlowski_et_al_2019  
**Category:** white   
**Used in Paper:** The Geometry of Culture: Analyzing Meaning through Word Embeddings (Kozlowski et al., 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [white, whites, Whites, White, European, Caucasian]

**Seeds ID:** female_names-Gonen_&_Goldberg_2019  
**Category:** female names   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [Amy, Joan, Lisa, Sarah, Diana, Kate, Ann, Donna]

**Seeds ID:** male_names-Gonen_&_Goldberg_2019  
**Category:** male names   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [John, Paul, Mike, Kevin, Steve, Greg, Jeff, Bill]

**Seeds ID:** family_words-Gonen_&_Goldberg_2019  
**Category:** family words   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [home, parents, children, family, cousins, marriage, wedding, relatives]

**Seeds ID:** career_words-Gonen_&_Goldberg_2019  
**Category:** career words   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [executive, management, professional, corpo-, ration, salary, office, business, career]

**Seeds ID:** arts_words-Gonen_&_Goldberg_2019  
**Category:** arts words   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [poetry, art, dance, literature, novel, symphony, drama, sculpture]

**Seeds ID:** math_words-Gonen_&_Goldberg_2019  
**Category:** math words   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [math, algebra, geometry, calculus, equations, computation, numbers, addition]

**Seeds ID:** arts_words_2-Gonen_&_Goldberg_2019  
**Category:** arts words 2   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [poetry, art, Shakespeare, dance, literature, novel, symphony, drama]

**Seeds ID:** science_words-Gonen_&_Goldberg_2019  
**Category:** science words   
**Used in Paper:** Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them (Gonen & Goldberg, 2019)  
**Source Categories:** prior-work  
**Link:** []()  
**Seeds:** [science, technology, physics, chemistry, Einstein, NASA, experiment, astronomy]

**Seeds ID:** sentiment_lexicon-Sweeney_&_Najafian_2019  
**Category:** sentiment lexicon   
**Used in Paper:** A Transparent Framework for Evaluating Unintended Demographic Bias in Word Embeddings (Sweeney & Najafian, 2019)  
**Source Categories:** lexical-resources  
**Link:** []()  
**Seeds:** []

**Seeds ID:** neutral_identity_terms-Sweeney_&_Najafian_2019  
**Category:** neutral identity terms   
**Used in Paper:** A Transparent Framework for Evaluating Unintended Demographic Bias in Word Embeddings (Sweeney & Najafian, 2019)  
**Source Categories:** corpus-derived  
**Link:** []()  
**Seeds:** []

**Seeds ID:** female_definition_words_1-Zhao_et_al_2018  
**Category:** female definition words 1   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [countrywoman, sororal, witches, maidservant, mothers, diva, actress, spinster, mama, duchesses, barwoman, countrywomen, dowry, hostesses, airwomen, menopause, clitoris, princess, governesses, abbess, women, widow, ladies, sorceresses, madam, brides, baroness, housewives, godesses, niece, widows, lady, sister, brides, nun, adultresses, obstetrics, bellgirls, her, marchioness, princesses, empresses, mare, chairwoman, convent, priestesses, girlhood, ladies, queen, gals, mommies, maid, female_ejaculation, spokeswoman, seamstress, cowgirls, chick, spinsters, hair_salon, empress, mommy, feminism, gals, enchantress, gal, motherhood, estrogen, camerawomen, godmother, strongwoman, goddess, matriarch, aunt, chairwomen, ma, am, sisterhood, hostess, estradiol, wife, mom, stewardess, females, viagra, spokeswomen, ma, belle, minx, maiden, witch, miss, nieces, mothered, cow, belles, councilwomen, landladies, granddaughter, fiancees, stepmothers, horsewomen, grandmothers, adultress, schoolgirl, hen, granddaughters, bachelorette, camerawoman, moms, her, mistress, lass, policewoman, nun, actresses, saleswomen, girlfriend, councilwoman, lady, stateswoman, maternal, lass, landlady, sistren, ladies, wenches, sorority, bellgirl, duchess, ballerina, chicks, fiancee, fillies, wives, suitress, maternity, she, businesswoman, masseuses, heroine, doe, busgirls, girlfriends, queens, sisters, mistresses, stepmother, brides, daughter, minxes, cowgirl, lady, daughters, mezzo, saleswoman, mistress, hostess, nuns, maids, mrs., headmistresses, lasses, congresswoman, airwoman, housewife, priestess, barwomen, barnoesses, abbesses, handywoman, toque, sororities, stewardesses, filly, czarina, stepdaughters, herself, girls, lionesses, lady, vagina, hers, masseuse, cows, aunts, wench, toques, wife, lioness, sorceress, effeminate, mother, lesbians, female, waitresses, ovum, skene_gland, stepdaughter, womb, businesswomen, heiress, waitress, headmistress, woman, governess, godess, bride, grandma, bride, gal, lesbian, ladies, girl, grandmother, mare, maternity, hens, uterus, nuns, maidservants, seamstress, busgirl, heroines]

**Seeds ID:** male_definition_words_1-Zhao_et_al_2018  
**Category:** male definition words 1   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [countryman, fraternal, wizards, manservant, fathers, divo, actor, bachelor, papa, dukes, barman, countrymen, brideprice, hosts, airmen, andropause, penis, prince, governors, abbot, men, widower, gentlemen, sorcerers, sir, bridegrooms, baron, househusbands, gods, nephew, widowers, lord, brother, grooms, priest, adultors, andrology, bellboys, his, marquis, princes, emperors, stallion, chairman, monastery, priests, boyhood, fellas, king, dudes, daddies, manservant, semen, spokesman, tailor, cowboys, dude, bachelors, barbershop, emperor, daddy, masculism, guys, enchanter, guy, fatherhood, androgen, cameramen, godfather, strongman, god, patriarch, uncle, chairmen, sir, brotherhood, host, testosterone, husband, dad, steward, males, cialis, spokesmen, pa, beau, stud, bachelor, wizard, sir, nephews, fathered, bull, beaus, councilmen, landlords, grandson, fiances, stepfathers, horsemen, grandfathers, adultor, schoolboy, rooster, grandsons, bachelor, cameraman, dads, him, master, lad, policeman, monk, actors, salesmen, boyfriend, councilman, fella, statesman, paternal, chap, landlord, brethren, lords, blokes, fraternity, bellboy, duke, ballet_dancer, dudes, fiance, colts, husbands, suitor, paternity, he, businessman, masseurs, hero, deer, busboys, boyfriends, kings, brothers, masters, stepfather, grooms, son, studs, cowboy, mentleman, sons, baritone, salesman, paramour, male_host, monks, menservants, mr., headmasters, lads, congressman, airman, househusband, priest, barmen, barons, abbots, handyman, beard, fraternities, stewards, colt, czar, stepsons, himself, boys, lions, gentleman, penis, his, masseur, bulls, uncles, bloke, beards, hubby, lion, sorcerer, macho, father, gays, male, waiters, sperm, prostate, stepson, prostatic_utricle, businessmen, heir, waiter, headmaster, man, governor, god, bridegroom, grandpa, groom, dude, gay, gents, boy, grandfather, gelding, paternity, roosters, prostatic_utricle, priests, manservants, stailor, busboy, heros]

**Seeds ID:** professions-Zhao_et_al_2018  
**Category:** professions   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** prior-work  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** []

**Seeds ID:** male_definition_words_2-Zhao_et_al_2018  
**Category:** male definition words 2   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** lexical-resources  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [rake, wizard, policeman, host, councilman, actor, waiter, businessman, fiance, spokesman, salesman, widower, horseman, governor, statesman, hero, chairman, headmaster, priest, gentleman, countrymen, nobleman]

**Seeds ID:** female_definition_words_2-Zhao_et_al_2018  
**Category:** female definition words 2   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** lexical-resources  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [lady, saleswoman, noblewoman, hostess, coquette, nun, heroine, actress, chairwoman, businesswoman, spokeswoman, waitress, councilwoman, stateswoman, policewoman, countrywomen, horsewoman, headmistress, governess, widow, witch, fiancee]

**Seeds ID:** male_stereotype_words-Zhao_et_al_2018  
**Category:** male stereotype words   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** lexical-resources  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [researcher, lawyer, developer, architect, dentist, doctor, boss, chef, programmer, president, pilot, guard, warrior, judge, janitor, captain, engineer, dispatcher, leader, manager]

**Seeds ID:** female_stereotype_words-Zhao_et_al_2018  
**Category:** female stereotype words   
**Used in Paper:** Learning gender-neutral word embeddings (Zhao et al., 2018)  
**Source Categories:** lexical-resources  
**Link:** [https://github.com/uclanlp/gn_glove](https://github.com/uclanlp/gn_glove)  
**Seeds:** [baker, counselor, nanny, librarians, socialite, assistant, tailor, dancer, hairdresser, cashier, secretary, clerk, stenographer, optometrist, housekeeper, bookkeeper, homemaker, nurse, stylist, receptionist]

**Seeds ID:** female-Rudinger_et_al_2017  
**Category:** female   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [woman, women, her, her, she]

**Seeds ID:** male-Rudinger_et_al_2017  
**Category:** male   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [man, men, him, his, he]

**Seeds ID:** black-Rudinger_et_al_2017  
**Category:** black   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [black, black_person, black_man, black_woman]

**Seeds ID:** white-Rudinger_et_al_2017  
**Category:** white   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [white, white_person, white_man, white_woman]

**Seeds ID:** hispanic-Rudinger_et_al_2017  
**Category:** hispanic   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [hispanic, hispanic_person, hispanic_man, hispanic_woman]

**Seeds ID:** asian-Rudinger_et_al_2017  
**Category:** asian   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [asian, asian_person, asian_man, asian_woman]

**Seeds ID:** career-Rudinger_et_al_2017  
**Category:** career   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [salary, career, business, office, professional, management, corporation, executive]

**Seeds ID:** violence-Rudinger_et_al_2017  
**Category:** violence   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [fight, fights, gun, guns, shoots, attacks, dangerous]

**Seeds ID:** female_2-Rudinger_et_al_2017  
**Category:** female 2   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [woman, women, girl, girls, mother]

**Seeds ID:** male_2-Rudinger_et_al_2017  
**Category:** male 2   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [man, men, boy, boys, father]

**Seeds ID:** old-Rudinger_et_al_2017  
**Category:** old   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [old, old_woman, old_man]

**Seeds ID:** young-Rudinger_et_al_2017  
**Category:** young   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [young, young_woman, young_man]

**Seeds ID:** race/ethnicity/nationality-Rudinger_et_al_2017  
**Category:** race/ethnicity/nationality   
**Used in Paper:** Social Bias in Elicited Natural Language Inferences (Rudinger et al., 2017)  
**Source Categories:** corpus-derived  
**Link:** [https://github.com/cjmay/snli-ethics](https://github.com/cjmay/snli-ethics)  
**Seeds:** [indian, indian_woman, indian_man, asian, asians, asian_woman, asian_man, whie_woman, white_man, caucasian, american, american_woman, american_man, black_woman, black_man, native_american, african_american, african]

**Seeds ID:** white_collar_job-Fast_et_al_2016  
**Category:** white_collar_job   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [detective, executive, scientist, biologist, surgeon, vet, office, photographer, employer, colleague, psychiatrist, psychologist, qualified, wealthy, businesswoman, manager, therapist, attorney, forensics, lawyer, employment, workaholic, coroner, nurse, specialist, internship, job, neurologist, senator, promotion, retired, researcher, profession, engineer, accountant, entrepreneur, paperwork, counselling, successful, dentist, analyst, physician, hire, politician, consultant, retire, veterinarian, supervisor, examiner, inspector, doctor, actor, pharmacist, chemist, pediatrician, pediatric, director, professional, law, salary, chief, gynecologist]

**Seeds ID:** blue_collar_job-Fast_et_al_2016  
**Category:** blue_collar_job   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [serving, maid, employer, employee, salesperson, payday, pizzeria, clerk, supermarket, job, attendant, restaurant, waiter, waitress, worker, bartender, hostess, receptionist, cashier, paycheck, barista]

**Seeds ID:** domestic_work-Fast_et_al_2016  
**Category:** domestic_work   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [chore, mom, vacuum, scrubbing, cook, washing, baking, wash, morning, meal, house, chef, laundry, bake, organizing, cooking, spotless, mum, washer, remodeling, parent, job, nanny, kitchen, dishwasher, cleaning, family, cleaner, bathroom, errand, sitter, housekeeper, serve, housekeeping, tidy, cleaned, housework, scrub, organize, home, clean]

**Seeds ID:** occupation-Fast_et_al_2016  
**Category:** occupation   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [detective, producer, executive, manager, therapist, actor, electrician, occupation, retirement, office, photographer, maid, cashier, colleague, psychiatrist, bodyguard, psychologist, qualified, supervise, politician, surgeon, policeman, businesswoman, server, journalist, housekeeper, secretary, attorney, choreographer, chef, intern, lawyer, interpreter, employment, retire, nurse, officer, specialist, working, hairdresser, internship, clerk, job, nanny, waiter, pediatrician, pediatric, neurologist, senator, waitress, retired, profession, entrepreneur, florist, workplace, service, accountant, worker, singer, catering, dentist, technician, analyst, physician, hire, bartender, hostess, consultant, employ, veterinarian, caterer, entertainer, supervisor, publicist, agent, concierge, coordinator, receptionist, accounting, inspector, doctor, owner, assistant, interview, pharmacist, chemist, foreman, employee, qualification, workaholic, businessman, salary, baker, banker, gynecologist, professional, policewoman]

**Seeds ID:** attractive-Fast_et_al_2016  
**Category:** attractive   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [alluring, cute, attractively, athletic, desirable, breathtaking, perfect, swoon, sexiest, sassy, attractive, masculine, pleasing, captivating, fantastic, dreamy, charmingly, glamorous, seductive, mesmerizing, inviting, hunk, popular, fascinating, flatter, supermodel, fabulous, irresistible, enticing, appealing, dimpled, looking, attracted, adore, appeal, adorable, compliment, revealing, dashing, fantasize, stylish, sexy, flawless, tempting, envious, angelic, lovable, marvelous, hotter, blonde, charismatic, classically, hunky, dazzling, gorgeous, lovely, chiseled, pretty, impress, charming, feminine, handsome, toned, photogenic, admire, stunning, charmer, coolest, beautiful, provocative, beautifully, attract, dazzle, breathtakingly, physique, strikingly, hot, luscious, buff, beauty, attractiveness, fashionable, enchanting, curvy, built, tanned]

**Seeds ID:** ugliness-Fast_et_al_2016  
**Category:** ugliness   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [despise, balding, slimy, acne, grotesque, degrading, horrible, fat, diseased, repulsive, awful, nasty, brutish, grotesquely, distasteful, unworthy, scruffy, chubby, gross, insulting, crooked, revolting, unappealing, hairy, pathetic, cockroach, abnormally, unsightly, crippled, lousy, wrinkled, freakish, disfigured, disgusting, pudgy, tacky, obese, disgust, degrade, horrid, deformed, hideous, bloated, ugly, scum, demeaning, pig, obnoxious, blob, wart, disgraceful, fatty, bald, overweight, disgusted, unattractive, wrinkle, filthy, loathsome]

**Seeds ID:** masculine-Fast_et_al_2016  
**Category:** masculine   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [alluring, cockiness, attractively, athletic, cocky, aggressive, tattooed, jock, arrogance, masculine, hormone, dominate, males, overpowering, dreamy, brutish, stereotypical, guy, bulky, scruffy, authority, manly, baritone, hunky, lad, masculinity, hunk, appeal, surfer, strong, boy, testosterone, domineering, male, youthful, dude, fella, distinct, charisma, man, chiseled, puberty, mentality, boys, shouldered, handsome, rugged, intimidate, stature, figure, intimidating, muscular, brawny, beefy, attract, physique, athletically, biceps, attractiveness, stocky, hormonal, burly, egotistical, bodied, rowdy]

**Seeds ID:** feminine-Fast_et_al_2016  
**Category:** feminine   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [cute, gown, haircut, slimming, lacy, stunningly, curled, pretty, redhead, appealing, wearing, woman, wavy, silk, stylist, nicely, tights, finery, cleavage, stylish, brunette, lilac, elegant, supermodel, fabulous, girl, perfume, matching, blouse, silky, ruffled, purple, bikini, revealing, voluptuous, hairdresser, complement, makeup, sexy, dress, headband, blazer, layered, perky, clothes, pair, blonde, pantyhose, comb, jewelry, fuchsia, styling, accentuate, gorgeous, girls, impress, sophisticated, flowery, slinky, glam, wardrobe, glamorous, girlish, voluminous, stunning, beautiful, hairstyle, fashion, provocative, chic, skirt, curl, ballerina, fashionable, dressed, kimono, skater, frilly, halter, accessory, floral, jewelry, feminine, curve, curvy, lipstick, skinny]

**Seeds ID:** positive_emotion-Fast_et_al_2016  
**Category:** positive_emotion   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [happiness, enlighten, better, enthusiasm, pride, joyful, compassion, dearly, forgiving, kindness, bravery, closure, thrill, honestly, triumph, bond, honesty, alive, concern, reunite, joy, surprise, forgiveness, assurance, sympathize, understanding, reason, rejoice, care, faith, great, empathy, certainty, keep, trustworthy, affection, cherish, emotion, love, family, trusting, respect, trust, gratitude, confidence, adoration, friend, happy, overjoyed, determination, reassurance, glad, loved, admiration, wish, accomplishment, optimism, excitement, convince, hope, freedom, feeling, eagerness, willingness, sincere, sincerity, honest, genuine, comfort, elation, thrilled, loyalty, curiosity, unconditionally, proud]

**Seeds ID:** negative_emotion-Fast_et_al_2016  
**Category:** negative_emotion   
**Used in Paper:** Empath: Understanding Topic Signals in Large-Scale Text (Fast et al., 2016)  
**Source Categories:** crowd-sourced, curated, lexical-resources  
**Link:** [https://github.com/Ejhfast/empath-client](https://github.com/Ejhfast/empath-client)  
**Seeds:** [violent, kill, hell, hate, dieing, death, thinking, hated, crying, surprised, hurting, worse, beat, stop, crushed, break, worst, trouble, disappointed, killed, lost, cry, worried, worst_part, bad, stupid, either, die, mean, insane, fucking, scared, hard, dead, beaten, horrible, monster, weak, loose, threatened, punch, killing, blame, reason, so_much_pain, hurts, losing, wanted, pissed, care, scary, accident, fault, guilty, terrible, swear, last_straw, heartbroken, scare, seeing, drunk, terrified, freaked, raped, frightened, poor_girl, lose, angry, fight, poor_guy, hurt, ashamed, depressed, unthinkable, tortured, crazy, confused, sad, hit, alone, lie, afraid, dying, shocked, angered, sick, badly, pain, react, wrong, mad, upset, fighting, furious]

**Seeds ID:** final_identities-Joseph_et_al_2017  
**Category:** final identities   
**Used in Paper:** Girls rule, boys drool: Extracting semantic and affective stereotypes on Twitter (Joseph et al, 2017)  
**Source Categories:** corpus-derived, curated  
**Link:** [https://github.com/kennyjoseph/twitter_stereotype_extraction](https://github.com/kennyjoseph/twitter_stereotype_extraction)  
**Seeds:** [detective, ambassador, coach, liar, sister, chinese, enemy, radical, stripper, bum, actress, russian, gf, manager, scientist, gunman, asian, victim, little, brother, mexican, prisoner, economist, mayor, principal, vet, instructor, police, buddy, candidate, feminist, photographer, father, police, officer, maid, indian, black, teenager, innocent, citizen, employee, speaker, supervisor, hater, colleague, woman, executive, teacher, jerk, civilian, ceo, assistant, advocate, coworker, patriot, vegan, arab, roommate, boxer, fan, mom, judge, politician, african, american, republican, lady, nurse, socialist, bro, toddler, scholar, pimp, artist, celebrity, sophomore, rapper, brother, clown, grandfather, spy, surgeon, priest, journalist, pilot, chick, guy, rich, grad, athlete, husband, secretary, user, prosecutor, attorney, nigga, female, japanese, democrat, chef, gangster, intern, individual, preacher, governor, lawyer, nephew, hero, girl, homeless, hacker, rapist, israeli, expert, announcer, rep, gentleman, conservative, grandmother, genius, activist, hipster, hooker, leader, juror, musician, bf, muslim, christian, bully, parent, reporter, lawmaker, white, man, middle, class, slut, boss, volunteer, bachelor, minor, rebel, grandma, worker, cousin, marine, loser, jew, cop, passenger, daughter, sheriff, survivor, canadian, thot, supporter, punk, host, millionaire, officer, soldier, american, taxpayer, murderer, mentor, neighbor, senator, virgin, protestor, voter, college, student, winner, family, deputy, blogger, singer, firefighter, intellectual, son, black, man, entrepreneur, follower, dancer, cheerleader, fool, liberal, blonde, employer, white, woman, engineer, killer, teammate, guest, sucker, dude, tourist, princess, inmate, runner, racist, editor, saint, mama, qb, man, pope, teen, commissioner, homosexual, champion, gay, boy, relative, farmer, pitcher, pastor, thief, poet, dentist, grandpa, adult, child, baby, niece, immigrant, junior, witness, boyfriend, customer, extremist, baptist, criminal, bartender, sibling, consultant, coward, believer, bride, hispanic, friend, lover, protester, daddy, dad, shooter, freak, angel, alcoholic, resident, pro, owner, player, critic, comedian, uncle, girlfriend, partner, nerd, hoe, native, catholic, bastard, author, idiot, veteran, producer, actor, hostage, patient, chairman, goon, moron, donor, asshole, latino, pal, rider, poor, thug, designer, minority, best, friend, stranger, professor, black, woman, vegetarian, terrorist, director, addict, student, writer, freshman, president, momma, spouse, lesbian, kid, geek, hypocrite, fighter, wife, atheist, doctor, white, academic, chief, client, aunt, mother, professional, guard, consumer, minister]

**Seeds ID:** verb_senses-Hoyle_et_al_2019  
**Category:** verb senses   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:**   
**Link:** []()  
**Seeds:** []

**Seeds ID:** male_singular-Hoyle_et_al_2019  
**Category:** male singular   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:** corpus-derived  
**Link:** []()  
**Seeds:** [man, boy, father, son, brother, husband, uncle, nephew, emperor, king, prince, duke, lord, knight, waiter, actor, god, policeman, postman, hero, wizard, steward, he]

**Seeds ID:** male_plural-Hoyle_et_al_2019  
**Category:** male plural   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:** corpus-derived  
**Link:** []()  
**Seeds:** [men, boys, fathers, sons, brothers, husbands, uncles, nephews, emperors, kings, princes, dukes, lords, knights, waiters, actors, gods, policemen, postmen, heros, wizards, stewards]

**Seeds ID:** female_singular-Hoyle_et_al_2019  
**Category:** female singular   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:** corpus-derived  
**Link:** []()  
**Seeds:** [woman, girl, mother, daughter, sister, wife, aunt, niece, empress, queen, princess, duchess, lady, dame, waitress, actress, goddess, policewoman, postwoman, heroine, witch, stewardess, she]

**Seeds ID:** female_plural-Hoyle_et_al_2019  
**Category:** female plural   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:** corpus-derived  
**Link:** []()  
**Seeds:** [women, girls, mothers, daughters, sisters, wives, aunts, nieces, empresses, queens, princesses, duchesses, ladies, dames, waitresses, actresses, goddesses, policewomen, postwomen, heroines, witches, stewardesses]

**Seeds ID:** personality_traits-Hoyle_et_al_2019  
**Category:** personality traits   
**Used in Paper:** Unsupervised Discovery of Gendered Language through Latent-Variable Modeling (Hoyle et al., 2019)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** []()  
**Seeds:** []

**Seeds ID:** feminine-Kaneko_and_Bollegala_2019  
**Category:** feminine   
**Used in Paper:** Gender-preserving Debiasing for Pre-trained Word Embeddings (Kaneko and Bollegala, 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/kanekomasahiro/gp_debias](https://github.com/kanekomasahiro/gp_debias)  
**Seeds:** []

**Seeds ID:** masculine-Kaneko_and_Bollegala_2019  
**Category:** masculine   
**Used in Paper:** Gender-preserving Debiasing for Pre-trained Word Embeddings (Kaneko and Bollegala, 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/kanekomasahiro/gp_debias](https://github.com/kanekomasahiro/gp_debias)  
**Seeds:** []

**Seeds ID:** gender-neutral-Kaneko_and_Bollegala_2019  
**Category:** gender-neutral   
**Used in Paper:** Gender-preserving Debiasing for Pre-trained Word Embeddings (Kaneko and Bollegala, 2019)  
**Source Categories:** curated  
**Link:** [https://github.com/kanekomasahiro/gp_debias](https://github.com/kanekomasahiro/gp_debias)  
**Seeds:** [abandonment, abate, aberrant, abiding, able, abolition, abomination, abrupt, absorbing, absorption, abstention, abstraction, absurd, absurdity, abundance, abundantly, accept, acceptable, access, accident, accidentally, accompany, accomplish, according, accordingly, account, accumulation, accurate, accuse, achieve, achievement, acid, acknowledge, acquire, actuality, adaptable, adaptation, addictive, adherence, adjacent, adjustable, adjustment, adjustments, admittedly, ado, adorable, adore, adorn, advancement, advent, adverse, adversity, advertisement, aerial, afar, affected, afternoon, ago, agonies, agree, agreement, agricultural, air, aircraft, airliner, airport, alarms, alongside, aloof, alternately, amazing, amazingly, amount, amusement, analogous, analyses, answer, apartments, apparatus, apparent, apparently, appetizer, apple, appoint, appointment, appreciate, approach, appropriate, approval, approve, approximately, argument, arms, arrests, art, ask, astray, attack, attempt, attention, attraction, attributes, authority, aware, back, backdrops, bad, balance, ballots, banana, bar, barely, barrel, base, battery, be, become, bed, before, beforehand, begin, beginning, behavior, behind, being, belief, believe, bell, belong, below, benches, benefits, best, better, big, bigger, biggest, billion, bit, bite, blackboard, blast, blizzard, blood, blouse, blow, blue, blues, board, boat, body, bomb, bombing, bond, bone, boon, bother, bottle, bottles, boxes, branch, brass, bread, breath, breeze, bright, brighter, building, bulletin, burn, burst, bus, buses, butter, bygone, calamity, calm, calmly, camera, camp, campaign, campus, can, cancer, candidate, canoe, canvas, cap, capability, capable, capacity, capital, capsule, captain, capture, car, carbon, card, cardboard, care, career, careful, carefully, carpet, carrier, carry, case, cash, cassette, cast, cataract, categorical, cathedral, cause, cell, center, centigrade, central, cerebellum, ceremonial, certain, certify, chair, chalk, chance, change, changing, channel, chapter, character, characteristic, characterize, charge, cheap, cheaper, cheapest, cheerful, cheerfully, chestnut, chin, china, choices, cinema, circuit, circulate, cities, city, clarify, clearance, clock, clumsy, coal, cocoon, coffee, coincide, cold, colder, color, come, comfort, comfortable, common, communicate, communication, community, compacts, company, comparison, competition, completion, compounds, condition, conference, confidence, confident, connection, consistent, control, conventional, conversation, coolest, copy, cork, corns, couch, cough, could, country, cover, crack, credit, creep, crime, crush, current, curve, daily, damage, damper, danger, dark, darkest, day, death, debate, debt, decade, decide, decided, decision, decrease, decreased, decreasing, deep, deeper, degree, denials, describe, described, describing, design, desire, destruction, detail, development, develops, different, digestion, direction, discover, discovering, discussion, disease, disgrace, disgust, disorder, display, dispute, distance, distant, distaste, distasteful, distinct, distinction, distinguish, distribute, distribution, district, diverse, diversity, divide, division, divorce, do, dodge, does, dollar, done, door, double, doubt, down, dream, dreams, dust, eagerly, ear, early, earn, earnings, earth, ease, easier, easily, east, eastern, easy, eat, eats, economic, edge, education, educations, effect, egg, end, enforcement, engage, english, enhance, enhanced, enhances, enhancing, equator, error, essentially, establish, establishment, estate, estimate, ethical, europe, evaporate, event, evidence, example, exchange, existence, expansion, experience, eye, eyelids, eyes, fact, fall, fast, faster, fear, fed, federal, fee, feed, feel, feeling, fellow, fiction, field, find, finds, finger, fire, flame, flashlight, flight, fly, flying, fold, food, force, form, free, freely, french, front, fruit, full, furniture, garbage, garlic, generate, generating, get, gets, give, glass, globe, go, goals, goes, going, gold, good, got, government, grain, grammar, grapefruit, grass, great, greater, greatest, green, grip, group, growth, half, hall, hand, handful, handle, hands, hang, hanger, happen, happily, happy, harbor, hard, harder, hardly, harmony, hate, have, head, heap, hear, hearing, heat, heavy, help, helps, hid, hidden, hill, history, hole, hope, hotel, hottest, hour, ice, idea, ideas, idiom, implement, importance, important, impose, impossible, impress, impression, impressions, impressive, improve, improvement, impulse, inconsistent, increase, increases, increasing, increasingly, incredible, indeed, industry, informative, ink, insect, insight, instinct, instrument, insurance, interest, international, invention, iron, is, issues, its, jar, join, jump, junction, keenly, keep, kept, killing, kit, knew, know, knowledge, known, label, ladders, land, language, largest, late, latent, laugh, lead, learning, leather, leave, leaves, leg, lemon, length, let, letter, level, lift, light, like, likes, limit, liquid, list, listen, listened, listening, listens, lists, live, load, local, london, long, longer, longest, look, looked, looking, loss, lounge, low, lower, lows, luck, luckiest, lucky, main, mainly, mains, mainstream, maintain, maintenance, major, majority, make, maker, many, margin, mark, may, meal, mean, measure, meat, meeting, memory, metal, middle, might, millionth, mind, minority, minute, miracle, mist, money, month, morning, motion, mountain, mouth, move, moved, mucus, multiple, museum, music, myriad, name, narrower, nation, national, necessarily, necessary, neck, need, net, new, newer, newly, news, nice, night, nightly, noise, noisier, noisiest, none, nonetheless, nor, normal, normally, nose, note, number, oases, observation, offer, oil, old, older, oldest, onion, onions, only, operation, opinion, order, organization, other, overflow, page, pain, paint, paper, part, particular, paste, payment, pen, pencil, pending, pepper, perfect, perfectly, perform, phenomena, phone, photo, pitches, place, play, pleasure, plenty, point, poison, pole, polish, pool, porter, position, possible, powder, power, predicts, price, print, problems, process, produce, productive, profit, property, prose, protest, pull, punishment, pupils, purpose, push, put, quality, question, quick, quicker, quickly, quieting, rain, rainfalls, range, rank, rapid, rapidly, rare, rarely, rate, ratios, raw, ray, reach, react, reaction, reading, real, reason, recent, recliner, recognize, recommend, recommendation, record, reflect, reflection, regret, relation, religion, remind, rent, reportedly, representative, request, resemblance, respect, rest, result, retain, reward, rhythm, rhythms, rice, right, river, road, roll, roof, room, rub, rule, run, running, safe, safely, safer, salt, sand, saw, say, says, scale, schedule, scheme, screamed, screaming, sea, seat, second, secretary, see, seeing, seem, seemingly, sees, selection, self, sense, sentence, serious, seriously, servant, seventh, several, shade, shake, shelf, shirt, shock, shoes, should, show, shuffle, shuffles, sick, side, siege, sign, silk, silver, simplest, size, skill, sky, sleep, sleeping, slept, slip, slope, slow, slower, slowing, slowly, smarter, smartest, smash, smell, smile, smoke, smoothing, sneeze, snow, society, some, song, sort, sound, space, speak, speaks, special, spending, stacks, stage, stanford, start, statement, steam, steel, step, stitch, stone, stones, stop, story, stress, stretch, stronger, structure, substance, sufficiently, sugar, suggestion, summer, support, surprise, swift, swiftly, swim, system, systems, take, talk, taste, tasteful, tax, teeth, tell, ten, tendency, test, text, then, theories, theory, thing, things, think, thinks, thought, thousand, thousandth, thump, thunder, time, tin, tissue, title, tokyo, tomatoes, tongue, took, top, touch, tougher, town, toy, trade, transfer, transport, tree, trick, trouble, try, turn, twist, unacceptable, unaware, uncomfortable, undecided, underside, unexpectedly, unfortunately, unimpressive, uninformative, unit, university, unknown, unproductive, use, useful, utterly, value, vanishes, variously, verse, very, vessel, view, visibility, visit, voice, walk, want, ware, warmer, was, wash, waste, water, watery, wave, way, weakest, weather, week, weekend, weeks, welfare, went, westward, whichever, whole, widest, will, wind, wine, winter, wire, wishes, wood, wool, word, words, world, worse, worst, would, wound, writing, yacht, year, yearly, yen, young, younger, youngest, zero, zigzag, zone]

**Seeds ID:** stereotypeical-Kaneko_and_Bollegala_2019  
**Category:** stereotypeical   
**Used in Paper:** Gender-preserving Debiasing for Pre-trained Word Embeddings (Kaneko and Bollegala, 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/kanekomasahiro/gp_debias](https://github.com/kanekomasahiro/gp_debias)  
**Seeds:** []

**Seeds ID:** male_names-Knoche_et_al_2019  
**Category:** male names   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [john, paul, mike, kevin, steve, greg, jeff, bill]

**Seeds ID:** female_names-Knoche_et_al_2019  
**Category:** female names   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [amy, joan, lisa, sarah, diana, kate, ann, donna]

**Seeds ID:** male_terms-Knoche_et_al_2019  
**Category:** male terms   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [male, man, boy, brother, he, him, his, son, father, uncle, grandfather]

**Seeds ID:** female_terms-Knoche_et_al_2019  
**Category:** female terms   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [female, woman, girl, sister, she, her, hers, daughter, mother, aunt, grandmother]

**Seeds ID:** male-Knoche_et_al_2019  
**Category:** male   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [john, paul, mike, kevin, steve, greg, jeff, bill, male, man, boy, brother, he, him, his, son, father, uncle, grandfather]

**Seeds ID:** female-Knoche_et_al_2019  
**Category:** female   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [amy, joan, lisa, sarah, diana, kate, ann, donna, female, woman, girl, sister, she, her, hers, daughter, mother, aunt, grandmother]

**Seeds ID:** white_names-Knoche_et_al_2019  
**Category:** white names   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [adam, chip, harry, josh, roger, alan, frank, ian, justin, ryan, andrew, fred, jack, matthew, stephen, brad, greg, jed, paul, todd, brandon, hank, jonathan, peter, wilbur, amanda, courtney, heather, melanie, sara, amber, crystal, katie, meredith, shannon, betsy, donna, kristin, nancy, stephanie, bobbie-sue, ellen, lauren, peggy, sue-ellen, colleen, emily, megan, rachel, wendy, brendan, geoffrey, brett, jay, neil, anne, carrie, jill, laurie, kristen, sarah]

**Seeds ID:** black_names-Knoche_et_al_2019  
**Category:** black names   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [alonzo, jamel, lerone, percell, theo, alphonse, jerome, leroy, rasaan, torrance, darnell, lamar, lionel, rashaun, tyree, deion, lamont, malik, terrence, tyrone, everol, lavon, marcellus, terryl, wardell, aiesha, lashelle, nichelle, shereen, temeka, ebony, latisha, shaniqua, tameisha, teretha, jasmine, latonya, shanise, tanisha, tia, lakisha, latoya, sharise, tashika, yolanda, lashandra, malika, shavonn, tawanda, yvette, hakim, jermaine, kareem, jamal, rasheed, aisha, keisha, kenya, tamika]

**Seeds ID:** christianity_words-Knoche_et_al_2019  
**Category:** christianity words   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [baptism, messiah, catholicism, resurrection, christianity, salvation, protestant, gospel, trinity, jesus, christ, christian, cross, catholic, church]

**Seeds ID:** islam_words-Knoche_et_al_2019  
**Category:** islam words   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [allah, ramadan, turban, emir, salaam, sunni, koran, imam, sultan, prophet, veil, ayatollah, shiite, mosque, islam, sheik, muslim, muhammad]

**Seeds ID:** atheism_words-Knoche_et_al_2019  
**Category:** atheism words   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [atheism, atheist, atheistic, heliocentric, evolution, darwin, galilei, agnostic, agnosticism, pagan, science, disbelief, scepticism, philosophy, university, kopernikus]

**Seeds ID:** pleasant-Knoche_et_al_2019  
**Category:** pleasant   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [caress, freedom, health, love, peace, cheer, friend, heaven, loyal, pleasure, diamond, gentle, honest, lucky, rainbow, diploma, gift, honor, miracle, sunrise, family, happy, laughter, paradise, vacation, joy, wonderful]

**Seeds ID:** unpleasant-Knoche_et_al_2019  
**Category:** unpleasant   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [abuse, crash, filth, murder, sickness, accident, death, grief, poison, stink, assault, disaster, hatred, pollute, tragedy, divorce, jail, poverty, ugly, cancer, kill, rotten, vomit, agony, prison, terrible, horrible, nasty, evil, war, awful, failure]

**Seeds ID:** science-Knoche_et_al_2019  
**Category:** science   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [math, algebra, geometry, calculus, equations, computation, numbers, addition, science, technology, physics, chemistry, einstein, nasa, experiment, astronomy]

**Seeds ID:** art-Knoche_et_al_2019  
**Category:** art   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [poetry, art, dance, literature, novel, symphony, drama, sculpture, shakespeare]

**Seeds ID:** intellectual_words-Knoche_et_al_2019  
**Category:** intellectual words   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [precocious, resourceful, inquisitive, sagacious, inventive, astute, adaptable, reflective, discerning, intuitive, inquiring, judicious, analytical, luminous, venerable, imaginative, shrewd, thoughtful, sage, smart, ingenious, clever, brilliant, logical, intelligent, apt, genius, wise, stupid, dumb, dull, clumsy, foolish, naive, unintelligent, trivial, unwise, idiotic]

**Seeds ID:** appearance_words-Knoche_et_al_2019  
**Category:** appearance words   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [alluring, voluptuous, blushing, homely, plump, sensual, gorgeous, slim, bald, athletic, fashionable, stout, ugly, muscular, slender, feeble, handsome, healthy, attractive, fat, weak, thin, pretty, beautiful, strong]

**Seeds ID:** career-Knoche_et_al_2019  
**Category:** career   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [executive, management, professional, corporation, salary, office, business, career]

**Seeds ID:** family-Knoche_et_al_2019  
**Category:** family   
**Used in Paper:** Identifying Biases in Politically Biased Wikis through Word Embeddings (Knoche et al., 2019)  
**Source Categories:** borrowed-from-social-sciences, prior-work  
**Link:** [https://github.com/MKnoche/wiki_bias_embedding](https://github.com/MKnoche/wiki_bias_embedding)  
**Seeds:** [home, parents, children, family, cousins, marriage, wedding, relatives]

**Seeds ID:** high_morality_and_low/neutral_warmth-Bhatia_et_al_2018  
**Category:** high morality and low/neutral warmth   
**Used in Paper:** Trait associations for Hillary Clinton and Donald Trump in news media:  A computational analysis (Bhatia et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** []()  
**Seeds:** [courageous, fair, principled, responsible, just, honest, trustworthy, loyal]

**Seeds ID:** low/neutral_and_morality_high_warmth-Bhatia_et_al_2018  
**Category:** low/neutral and morality high warmth   
**Used in Paper:** Trait associations for Hillary Clinton and Donald Trump in news media:  A computational analysis (Bhatia et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** []()  
**Seeds:** [warm, sociable, happy, agreeable, enthusiastic, easygoing, funny, playful]

**Seeds ID:** high_competence-Bhatia_et_al_2018  
**Category:** high competence   
**Used in Paper:** Trait associations for Hillary Clinton and Donald Trump in news media:  A computational analysis (Bhatia et al., 2018)  
**Source Categories:** borrowed-from-social-sciences  
**Link:** []()  
**Seeds:** [athletic, musical, creative, innovative, intelligent, organized, logical, clever]

**Seeds ID:** male_words_Penn_Treebank-Bordia_and_Bowman_2019  
**Category:** male words (Penn Treebank)   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actor,
boy,
father,
he,
him,
his,
male,
man,
men,
son,
sons,
spokesman,
wife,
king,
brother]

**Seeds ID:** female_words_Penn_Treebank-Bordia_and_Bowman_2019  
**Category:** female words (Penn Treebank)   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actress,
girl,
mother,
she,
her,
her,
female,
woman,
women,
daughter,
daughters,
spokeswoman,
husband,
queen,
sister]

**Seeds ID:** male_words_WikiText_2-Bordia_and_Bowman_2019  
**Category:** male words (WikiText-2)   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actor,
Actor,
boy,
Boy,
boyfriend,
Boys,
boys,
father,
Father,
Fathers,
fathers,
Gentleman,
gentleman,
gentlemen,
Gentlemen,
grandson,
he,
He,
hero,
him,
Him,
his,
His,
Husband,
husbands,
King,
kings,
Kings,
male,
Male,
males,
Males,
man,
Man,
men,
Men,
Mr.,
Prince,
prince,
son,
sons,
spokesman,
stepfather,
uncle,
wife,
king]

**Seeds ID:** female_words_WikiText_2-Bordia_and_Bowman_2019-Bordia_and_Bowman_2019  
**Category:** female words WikiText-3   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actress,
Actress,
girl,
Girl,
girlfriend,
Girls,
girls,
mother,
Mother,
Mothers,
mothers,
Lady,
lady,
ladies,
Ladies,
granddaughter,
she,
She,
heroine,
her,
Her,
her,
Her,
Wife,
wives,
Queen,
queens,
Queens,
female,
Female,
females,
Females,
woman,
Woman,
women,
Women,
Mrs.,
Princess,
princess,
daughter,
daughters,
spokeswoman,
stepmother,
aunt,
husband,
queen]

**Seeds ID:** male_words_CNN_DailyMail-Bordia_and_Bowman_2019  
**Category:** male words (CNN/Daily Mail)   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actor,
boy,
boyfriend,
boys,
father,
fathers,
gentleman,
gentlemen,
grandson,
he,
him,
his,
husbands,
kings,
male,
males,
man,
men,
prince,
son,
sons,
spokesman,
stepfather,
uncle,
wife,
king,
brother,
brothers]

**Seeds ID:** female_words_CNN_DailyMail-Bordia_and_Bowman_2019  
**Category:** female words (CNN/Daily Mail)   
**Used in Paper:** Identifying and Reducing Gender Bias in Word-Level Language Models (Bordia and Bowman, 2019)  
**Source Categories:** curated  
**Link:** []()  
**Seeds:** [actress,
girl,
girlfriend,
girls,
mother,
mothers,
lady,
ladies,
granddaughter,
she,
her,
her,
wives,
queens,
female,
females,
woman,
women,
princess,
daughter,
daughters,
spokeswoman,
stepmother,
aunt,
husband,
queen,
sister,
sisters]

**Seeds ID:** words_to_debias-Kumar_et_al_2020  
**Category:** words to debias   
**Used in Paper:** Nurse is Closer to Woman than Surgeon? Mitigating Gender-BiasedProximities in Word Embeddings (Kumar et al., 2020)  
**Source Categories:** prior-work  
**Link:** [https://github.com/TimeTraveller-San/RAN-Debias](https://github.com/TimeTraveller-San/RAN-Debias)  
**Seeds:** []

**Seeds ID:** male_identity-Park_et_al_2018  
**Category:** common gender identity pairs (male)   
**Used in Paper:** Reducing Gender Bias in Abusive Language Detection (Park et al., 2018)  
**Source Categories:** unknown  
**Link:** []()  
**Seeds:** []

**Seeds ID:** female_identity-Park_et_al_2018  
**Category:** common gender identity pairs (female)   
**Used in Paper:** Reducing Gender Bias in Abusive Language Detection (Park et al., 2018)  
**Source Categories:** unknown  
**Link:** []()  
**Seeds:** []

**Seeds ID:** neutral-Park_et_al_2018  
**Category:** neutral nouns and adjectives   
**Used in Paper:** Reducing Gender Bias in Abusive Language Detection (Park et al., 2018)  
**Source Categories:** unknown  
**Link:** []()  
**Seeds:** []

**Seeds ID:** offensive-Park_et_al_2018  
**Category:** offensive nouns and adjectives   
**Used in Paper:** Reducing Gender Bias in Abusive Language Detection (Park et al., 2018)  
**Source Categories:** unknown  
**Link:** []()  
**Seeds:** []
