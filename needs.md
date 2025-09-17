# **Guide to Inclusive Design: Needs and Solutions for Various Disabilities**

## **Aging**

### Considerations when creating solutions for people who are aging:
*   **Recognise that after age 25, individuals lose 8% of their ability to navigate the web efficiently every 10 years.**
*   **Be aware that older people are more likely to have disabilities**. Estimates range from approximately 30% to 60% of older populations, compared to 10%-20% for the population as a whole. Countries with large aging populations are likely to have a greater proportion of people with disabilities. For instance, in New Zealand (2013), 59% of people aged 65 or over had a disability, compared to 11% for children under 15 and 21% for adults under 65. In the U.S. (2013), 36% of persons aged 65+ had any disability.
*   **Understand that individuals aged 65 and over commonly experience disabilities related to** ambulatory function (66.5%), hearing (40.4%), cognitive abilities (28.8%), self-care (28.4%), independent living (47.8%), and vision (19.2%). For those aged 85 and over, 24.9% have vision disabilities, 48.1% have hearing disabilities, 39.1% have cognitive disabilities, 72.8% have ambulatory disabilities, 42.4% have self-care disabilities, and 68.7% have independent living disabilities.
*   **Design solutions to accommodate the gradual decline in various sensory, motor, and cognitive functions that can come with age**. This includes age-related forgetfulness, where individuals may take longer to learn new things, forget something but remember it later, or occasionally forget specific words. This differs from dementia, where forgetfulness is more pronounced and due to a disorder.
*   **Be mindful that older users may find new technical things, updated design patterns, and applications hard to learn and less intuitive**. Navigation may take longer.
*   **Support will be needed for age-related forgetfulness, which can impact memory and attention**. Clear headings, consistent designs, and familiar interfaces are beneficial.
*   **Consider that older users may struggle with online banking and shopping due to math skills not being as sharp** and worries about financial risk. They need to feel safe and supported, benefiting from autocomplete in forms, clear information about costs, and security features like spending limits.
*   **Design feedback mechanisms to be easy to find and use**, as older users may struggle with complex forms and phone menus when trying to provide feedback or get support.

## **Auditory Disabilities** 
**(Hearing Impairments, Hearing Loss, Deafness, Central Auditory Processing Disorder (ADP))**

### Considerations when creating solutions for people with auditory disabilities:
*   **Provide synchronized captions with videos**.
*   **Provide sign language interpretation** for videos, recordings, speeches, and talks.
*   **Provide a transcript** for audio content and recordings. Transcripts are necessary to convey all information from audio, including dialogue, narration, musical cues, and sound effects.
*   **Offer alternative visual alerts, such as lights that flash, pulse, dim, turn on, or turn off**, for sounds like doorbells and alarms.
*   Recognise that for people born with deafness, sign language is often their first language, which may influence their web experience. For this group, sign language interpretation may be preferred over captions and transcripts.

## **Blindness**

### Considerations when creating solutions for people who are blind:
*   **All content must be presented in text or via a text equivalent** (e.g., alt text for images or other non-text objects), because screen readers cannot directly read non-text content.
*   **Information must not be conveyed by visual attributes alone** (e.g., colour, spatial location, text thickness, background highlighting), as not all visual information is available to screen readers.
*   **All functionality must be available using only the keyboard**, as blind users navigate more effectively by keyboard than by mouse.
*   **Content must use markup with good structure and semantics** (headings, landmarks, tables, lists) to assist screen reader users in understanding and navigating the page.
*   **All custom controls** (e.g., expand/collapse buttons, media player volume control, dialogs) **must have the correct name/label, role, and value**, and change value when appropriate, using HTML or ARIA.
*   **Users must receive immediate feedback after all actions** via their screen reader; silence after activating a feature is undesirable.
*   **Videos require audio descriptions** (additional narration of visual content) if the original audio track does not explain everything a blind person needs to understand the video.
*   On mobile devices, **all features require a click action**, and custom swipe actions will not work with screen readers turned on.
*   Design interfaces and content to be compatible with **screen readers** by editing markup. Screen readers convert digital text to synthesised speech, but do not announce text styles like font, colour, size, bold, or italic.
*   **Self-voicing interfaces and applications** can broadcast information without a screen reader, but are mainly for broadcasting, not interaction.
*   **Refreshable braille output devices** convert digital text to braille, though they are expensive and only a minority of blind people read braille.
*   For printed materials, ensure information is available **online or in other digital formats** to allow access via assistive technologies.
*   For complex images or graphs, provide **brief (up to 150 characters) and longer descriptions**.
*   Identify **decorative or redundant images** and instruct developers to hide them from assistive technologies.
*   For physical navigation in built environments, provide **canes**, **service animals**, **GPS-based walking instructions with audio interfaces**, **raised tiles** to indicate pathways, and **eliminate low-hanging architectural features** and obstructions to ensure clear pathways.
*   For signs and text on buildings, utilise **map and geolocation applications with audio announcements**, **Braille labels and descriptions** (ensuring they are easy to find and readable), and **tactile models** of buildings or floorplans.
*   For consumer devices with flat interfaces (e.g., microwaves, ovens), offer **alternative interfaces with tactile controls (knobs), audio interfaces, or remote control via mobile applications**.
*   For product packaging, use **embossed Braille** (or Braille stickers) to help identify items.
*   For currency, provide **mobile applications that photograph and read the value of money** or manufacture **paper bills and coins in different sizes, shapes, or textures** to allow distinction by touch. Non-cash payment systems accessible with screen readers are also beneficial.
*   Utilise **Optical Character Recognition (OCR) software** to convert scanned images of text into digital text readable by screen readers. Accuracy depends on document quality, font choices, line spacing, and software quality.

## **Color Blindness**

### Considerations when creating solutions for people who are colourblind:
*   **All information must be understandable without needing to distinguish between colours**, as certain combinations (especially red-green) can be difficult to perceive. The most common types are Deuteranopia and Protanopia (red-green), with Tritanopia (blue-yellow) and Achromatopsia (seeing in grayscale) being less common.
*   **Do not rely on colour alone to communicate information**. For instance, a pie chart with different coloured slices should also include text labels for each slice. This ensures people who are colourblind do not miss important information.
*   **Be aware that red-black colours can also pose problems for some individuals**.
*   **Assistive technology, such as EnChroma glasses, may help compensate for some types of colour blindness**.

## **Cognitive Disabilities** 
**(including limited comprehension, low tolerance for cognitive overload, limited problem-solving skills, short-term memory loss, attention deficit, math anxiety, dyslexia, ADHD, autism, dementia, intellectual disabilities, specific learning disabilities, brain injury)**

Cognitive and learning disabilities impact how people process information, affecting perception, memory, language, attention, problem solving, and comprehension. This category includes intellectual disabilities, developmental disabilities, Attention Deficit Hyperactivity Disorder (ADHD), autism, dementia, dyslexia, and more. These can be congenital, developmental, or result from traumatic injury, infections, or chemical imbalances. People with cognitive and learning disabilities may also have other impairments, such as motor or visual impairments.

### Considerations when creating solutions for people with cognitive disabilities:
*   **Help users understand what things are and how to use them**. This includes using familiar icons, symbols, terms, and design patterns, such as standard hyperlink conventions (underlined and blue for unvisited, purple for visited).
    *   **Make the purpose of your page clear** with a clear title or heading. Provide information on how users arrived at the page (e.g., breadcrumbs, selected tab highlighting).
    *   **Use a familiar hierarchy and design** with common design elements, affordances, patterns, layout, and visual hierarchy (e.g., search in top right, home link in top left, submit button at bottom of form). Allow users to revert to prior versions of an application if they are familiar with them. Links should look like links (underlined, distinct colour) and buttons should look and act like buttons.
    *   **Use a consistent visual design** across groups of pages, including design themes, heading styles, font choices, icons, colours, and visual appearance of controls, buttons, and links. Layout and structure should be consistent.
    *   **Make each step clear** by providing breadcrumbs, a "how I got here" button, or headings to help users orient themselves within a site or task. In multi-step processes, clearly show completed, current, and pending steps, and any important choices.
    *   **Clearly identify controls and their use** with a clear and recognizable design, common styles, and sufficiently large click targets. Items that are not clickable should not look like controls. Provide instructions for non-standard controls.
    *   **Make the relationship clear between controls and the content they affect** by visually grouping them, including controls within their affected region, and using clear dividers or white space. Avoid multiple or nested scrolling areas.
    *   **Use icons that help the user** by adding familiar images and symbols to important content like controls and section headings. Icons should convey a single meaning and be next to the related content. For left-to-right languages, place images to the left of text; for multiple symbols in a section, place them above the text. Use personalisation semantics to load familiar symbols.
*   **Help users find what they need**. Navigating the system should be easy with a clear and easy-to-follow layout and visual cues.
    *   **Make it easy to find the most important tasks and features** on the site by making them stand out visually and programmatically. Place them towards the top of the page, use call-out boxes, and include them at the top level of main navigation.
    *   **Make the site hierarchy easy to understand and navigate** by organising content into logical sections and using clear, logical menu structures. Clearly indicate sub-menus with visual indicators.
    *   **Use a clear and understandable page structure** with logical sections, clear differentiation of regions (dividing lines, whitespace, background colours), and headings. Visual indicators should help understand structure, grouping, and purpose.
    *   **Make it easy to find the most important actions and information on the page** without scrolling or hovering, such as critical tasks, interactive features (login forms, send buttons), and health warnings.
    *   **Break media into chunks** that are logical, short (typically 6 minutes or less), labeled, and easy to identify and jump to, with navigation provided for each segment.
    *   **Provide search functionality** that is user-friendly, ideally including autocomplete, grouping of results with headings, ability to find previous searches, and spell-checking.
*   **Use clear and understandable content**. This involves easy words, short sentences, short blocks of text, unambiguous content, clear images, and easy-to-understand videos.
    *   **Use clear words** that are common and easy to understand, removing unnecessary or vague words, and explaining uncommon acronyms, abbreviations, and jargon. Avoid inventing new words or giving existing words new meanings. Provide explanations for uncommon words (e.g., simple language in brackets, pop-up definitions).
    *   **Use a simple tense and voice** (e.g., present tense and active voice in English) and speak directly to the user.
    *   **Avoid double negatives or nested clauses** to maintain simple sentence structure.
    *   **Use literal language** and concrete terms, avoiding metaphors and similes unless explained. Explain implied or ambiguous information in non-text media (e.g., body gestures, emotions, sarcasm, facial expressions) with text or separate tracks.
    *   **Keep text succinct** by using short paragraphs (one topic per paragraph, aim at the beginning), short sentences (one point per sentence), bulleted/numbered lists, and short descriptive headings.
    *   **Use clear, unambiguous formatting and punctuation** that reduces ambiguity and improves readability. Use language tags, punctuation correctly for prosody in speech conversion, and avoid Roman numerals or unfamiliar symbols unless correctly marked up. Display phone numbers and zip codes with appropriate layout and context. Dates should be clear across cultures.
    *   **Include symbols and letters necessary to decipher the words**, especially in languages like Arabic and Hebrew where optional vowels or diacritic marks are crucial for unambiguous pronunciation.
    *   **Provide a summary of long documents and media** that is brief, easy to understand, uses common words, and highlights keywords. Summaries for media help users with short attention spans locate content.
    *   **Separate each instruction** into clear, numbered or bulleted steps, including "obvious" ones. Use if/then tables for complex instructions.
    *   **Use white space** around objects and text to reduce clutter, provide definition, and aid navigation and reading. Allow users to adjust white space.
    *   **Ensure foreground content is not obscured by background** by using solid backgrounds for text and avoiding busy or distracting backgrounds for text and auditory content. Provide options to remove background noise in audio.
    *   **Explain implied content** by providing definitions or explanations for implied or ambiguous information such as body gestures, emotions, jokes, sarcasm, metaphors, similes, and facial expressions. These should be provided in text close to the implied content or in the markup.
    *   **Provide alternatives for numerical concepts** where math understanding is not primary, such as non-math textual explanations or qualitative terms (e.g., "cold," "warm," "hot") instead of numbers.
*   **Help users avoid mistakes and know how to correct them**.
    *   **Ensure controls and content do not move unexpectedly** unless initiated by the user or as part of essential activity. Display a "loading" indicator if content changes during a page load.
    *   **Let users go back** to a previous point without losing work, preferably using the standard back button.
    *   **Notify users of fees and charges at the start of a task** and provide terms and conditions in easy language.
    *   **Design forms to prevent mistakes** by requiring minimal information, clearly indicating required fields, accepting various input formats, dividing long numbers into chunks, using interfaces where only valid input can be selected, and using autocomplete. Automatically correct errors where reliable.
    *   **Make it easy to undo form errors** by allowing users to check and correct mistakes easily, and return to their previous location without redoing steps. For financial transactions, provide clear instructions for cancelling.
    *   **Use clear visible labels** that are in common, easy-to-understand language, visible, next to the relevant control, and readable by assistive technologies.
    *   **Use clear step-by-step instructions** located before or next to the field/activity, with examples or illustrations.
    *   **Accept different input formats** for values like currency, time zones, addresses, or credit card numbers to reduce errors.
    *   **Avoid data loss and "Timeouts"** by allowing users to save work or providing unlimited time. If timeouts are necessary, inform users at the start of the process about time limits and data loss.
    *   **Provide immediate feedback** on the status of each step and successful completion of actions. Use consistent and familiar design patterns for feedback.
    *   **Help the user stay safe** by understanding risks for people with cognitive disabilities when providing personal information or communicating online. Use known security techniques and explain risks in easy-to-understand language.
    *   **Use familiar metrics and units** (e.g., feet or meters) and provide options to change units and default to the user's location.
*   **Help users focus**. Avoid distracting content or elements and provide clear headings and breadcrumbs for reorientation.
    *   **Limit interruptions** by providing easy ways to control or limit distracting content (social media, violent content, advertisements, moving content, loud noises, triggers) unless user-initiated or emergency-related. Provide a quiet and simple environment.
    *   **Make critical paths short** by streamlining processes and workflows to include only necessary steps, separating optional steps.
    *   **Avoid too much content** by keeping interfaces simple, providing five or fewer main choices on each screen, and removing unnecessary content (e.g., in a simplified version).
    *   **Provide information to help a user complete and prepare for a task**, emphasizing the start of important tasks and giving estimates of effort, time, resources needed, and an overview of the process.
*   **Ensure processes do not rely on memory**. Avoid barriers like complex voice menus or remembering passwords.
    *   **Provide a login that does not rely on memory or other cognitive skills** (e.g., memorising strings, calculations, copying content, solving puzzles). Use alternatives like hardware authentication, trusted device login, biometrics, or third-party authentication.
    *   **Allow the user a simple, single-step login** alternative.
    *   **Provide a login alternative with fewer words** for users with language impairments.
    *   **Let users avoid navigating voice menus** by providing an easy way to reach a human (e.g., a known word or reserved digit like "0") at any time. Design helpful voice menus with clear options, pauses, and simple error recovery.
    *   **Do not rely on users' calculations or memorizing information** across multiple steps. Each step should contain necessary information, and systems should support slow responses and simple, one-word answers for voice interfaces.
*   **Provide help and support**. Support different ways of understanding content (graphics, summaries, icons, numerical alternatives).
    *   **Provide human help** that is easy to find on each page/step, easy to use via preferred methods (form, email, chat, phone directly to a human), and does not require complex menu systems.
    *   **Provide alternative content for complex information and tasks**, such as summaries, explanations of choices, tables, charts, familiar symbols, well-structured videos, pictures, and informational graphics. Provide an easy, single-action mechanism to select preferred content formats.
    *   **Clearly state the results and disadvantages of actions, options, and selections**, including benefits, risks, and consequences.
    *   **Provide help for forms and non-standard controls** with examples and easy-to-understand instructions, especially for multi-step or complex forms.
    *   **Make it easy to find help and give feedback** at any point in a process, using simple forms and preferred communication methods.
    *   **Provide help with directions** for navigational systems, including easily recognised landmarks, cardinal directions, and options to avoid unwanted changes (e.g., rerouting). Allow for reorientation and support different ways of perceiving distances.
    *   **Provide reminders** for date and time-sensitive events at the user's request, using standard APIs and allowing personalization of reminder methods. Do not add unwanted reminders.
*   **Support adaptation and personalization**. Users should be able to use add-ons and extensions as assistive technology.
    *   **Let users control when the content moves or changes** (context, functionality, settings, route, orientation). Provide an easily available mechanism to turn off such changes or return to previous states.
    *   **Enable APIs and extensions** to work with content, supporting features like spell checkers, password management, text-to-speech with highlighting, content simplification, and adding personalized images/symbols.
    *   **Support simplification** of content by allowing users to remove or hide non-essential features, get less text or simpler text, or select preferred content formats. Provide access to extra features when wanted.
    *   **Support a personalised and familiar interface** by allowing user preferences for presentation (font style, size, line heights, margins, contrast) and rollback to previous interfaces. Add semantics to controls, links, and symbols for user control. Ensure personalization options are easy to find and configure.
*   **Test with real users** with cognitive and learning disabilities in research, design, and development processes. Usability testing should measure efficacy, efficiency, and satisfaction for key tasks. This includes individuals with memory impairment, learning difficulty, attention impairment, numeric impairment, language and communication disability, and intellectual disability. Informed consent must be obtained, ensuring participants understand the project, risks, and their voluntary participation.

## **Deafblindness**

### Considerations when creating solutions for people who are deafblind:
*   **All considerations for blindness apply**, including the use of screen readers with refreshable braille displays.
*   **All considerations for deafness apply**, meaning alternative means to access audio content should be provided, particularly in a text-based format.
*   **A transcript must be provided for all audio and video content**. Transcripts are the only way deafblind individuals can access all information from these formats, given that captions may not work well with refreshable braille displays.

## **Dyslexia / Reading Disabilities**

### Considerations when creating solutions for people with dyslexia or reading disabilities:
*   **Supplement text with illustrations, videos, or audio**.
*   **Avoid the highest level of contrast for text against background** (e.g., pure black on white), while still ensuring it meets contrast requirements for low vision (e.g., dark grey against white or off-white may be easier to read). High contrast may be difficult to read and hard on the eyes.
*   Can benefit from **special fonts developed for Dyslexia** that modify letter appearance to prevent visual distortion and help keep words in line.
*   Allow users to **change the font, contrast, or add an underline to text** to help keep words in line.
*   May require **additional time to read and process content**.
*   Can use a **screen reader to get content in an auditory method** to reinforce what is being seen.
*   Screen readers that **highlight the word or phrase being read** can assist with tracking.
*   Use **enhanced visible focus indicators** to help track their position on the page.
*   Can use **special programs or dictionaries that present words with pictures**.
*   Allow users to **apply a custom style sheet**.
*   Provide the **ability to change the type of problem presented** for security features such as CAPTCHA.
*   Can use a **spelling and grammar checker**.
*   **Adjustable line spacing** can make text easier to follow.
*   **Content reflow** is crucial when zooming in significantly, ensuring elements stack and content remains usable.
*   **Avoid clutter or background imagery** to improve readability.
*   **Left-justified text with uneven right edges** can help with tracking.
*   **Short, simple sentences and easy words** are preferred, especially when reading fluently is a challenge.

## **Low Vision**

### Considerations when creating solutions for people with low vision:
*   **The pinch-to-zoom feature must not be disabled**. Disabling zooming prevents low vision users from properly magnifying content and may render information unusable.
*   **All text must pass contrast guidelines against the background** (minimum 4.5:1 for small text, 3:1 for large text). Stronger contrast is always better for users who may see in low contrast. Use tools to verify contrast ratios.
*   **Links, buttons, and controls must have a visible :focus state** and should have a **visible :hover state**. Enhanced CSS focus and hover states significantly benefit sighted keyboard users and low vision users to know where keyboard/mouse focus is.
*   The **user interface should provide a clear visual distinction between content (e.g., text) and controls (e.g., buttons, links)**, as low contrast can make these elements blend together.
*   Small text can be made easier to read with **screen magnifiers**.
*   **Software or hardware options to enhance contrast, change colours, or alter other aspects of visual appearance** can improve legibility.
*   **Screen readers can supplement screen magnifiers** by reading interfaces and content aloud, but only if the digital information is designed accessibly.
*   **Self-voicing interfaces and applications** can broadcast information effectively.
*   Provide **alternative large print versions of small print text**.
*   Provide **alternative digital versions of printed materials** (web, mobile applications) to allow users to access them with their own assistive technologies.
*   **Real text is important** because it can be magnified significantly without loss of clarity, and users can customise their colour schemes. Avoid images of text, with the exception of text within a logo.
*   **Non-text elements that are interactive or convey information** (e.g., visual focus indicators, lines in charts, custom controls, form elements, icons) **must have good colour contrast** to distinguish them from the background.

## **Motor Disabilities**
**(e.g., limited motor control, dexterity disabilities, tremors, spasms, temporary injury, obesity, ADHD affecting fine motor control, cerebral palsy, ALS, hemiplegia)**

Motor disabilities can range from a temporary inability to use one hand to difficulty using both hands (dexterity disability) or having little to no motor control. Individuals like Stephen Hawking and Marie-France Bru (ALS) used assistive technologies based on minimal muscle movement (cheek, jaw) to interact with computers. Paul Smith (cerebral palsy) used a typewriter to create art despite spastic, difficult-to-control movements.

### Considerations when creating solutions for people with motor disabilities:
*   **All functionality must be available using only the keyboard**. Individuals with motor disabilities may lack the fine motor skills required for a mouse or use devices that emulate keyboards. This includes controlling web pages using speech recognition software.
*   **Links, buttons, and controls must have a visible :focus state** and should have a **visible :hover state**. Enhanced CSS focus and hover states significantly benefit sighted keyboard users.
*   For session time-outs, **warn users before the time expires** with an accessible dialog or alert, and **give them the option to extend the session**. The warning itself should allow for slow responses (a minimum response time of 2 minutes is recommended). People with motor disabilities need more time to enter information.
*   **Provide large click targets (links, buttons, controls)** for users who have movements that are difficult to control (e.g., tremors or spasms). Increasing the target area maximises chances of accurate selection.
*   **Minimise tab stops** in keyboard navigation to improve efficiency for users who may find repeated key presses painful.
*   Implement **safeguards for accidental key presses** to prevent users from being taken to an unintended context.
*   **Allow users to cancel an operation** (e.g., by sliding the mouse or finger away after clicking/touching).
*   **Maintain a logical and intuitive tab order** for keyboard navigation.
*   For users unable to use a mouse, ensure compatibility with **alternative keyboards (e.g., vertical, one-handed, expanded), mouth sticks, single switch devices, speech recognition software, and eye-tracking technologies**.
*   For wheelchair users, provide **accessible ramps and elevators** in addition to steps, and ensure **accessible parking**. Accessible routes within and outside buildings should be labelled.
*   **Doors, hallways, rooms, and restrooms should be wide enough** to accommodate wheelchair users and other mobility devices, and corridors should be unobstructed.
*   For difficulty opening doors, provide **automatic doors, doors that can be opened using a large button, or lever-type handles/doorknobs**.
*   **Ensure seating can accommodate a variety of body sizes** (e.g., for individuals with obesity).
*   Provide **digital formats for printed materials** to allow access via assistive technologies or touch screen interfaces.
*   **Provide alternatives to device motion or gesture actuation** (e.g., shaking, tilting, specific gestures) as the primary control method; keyboard accessibility is the gold standard.
*   Allow users to **disable motion actuation** while retaining full system operation, for those with uncontrolled muscle movements.
*   Ensure the **page orientation can adapt** to a user's device orientation preferences (e.g., portrait/landscape) without forcing a specific mode.
*   Offer an option to **turn off parallax effects** and other animations for users with vestibular disorders or general discomfort.
*   **A consistent back or undo function** is crucial for users with eye-hand coordination difficulties or those who frequently make mistakes by pressing the wrong buttons.

## **Multiple/Compound Disabilities**

### Considerations when creating solutions for people with multiple or compound disabilities:
*   **Accessibility must be rooted in the individual's specific needs**, as combinations and degrees of disabilities vary greatly. Multiple disabilities refer to a combination of two or more, which may involve speech, motor, visual, hearing, learning, or intellectual disabilities. The impact of combined disabilities and their accommodation is key, rather than just the number of disabilities.
*   **Communication should be supported through augmentative and alternative communication (AAC)** such as sign language, tangible symbols, or computer-generated speech.
*   Individuals may benefit from **assistive technologies** to help overcome functional limitations and support communication.
*   **Providing support for both augmentative and alternative communication and assistive technologies, and following accessibility standards, are key** for making physical and technological environments more accessible.

## **Psychological/Psychiatric Disabilities**
**(including Anxiety Disorders, Mood Disorders, ADHD, Personality Disorders, Eating Disorders, Schizophrenia, Post-Traumatic Stress Disorder, Obsessive-Compulsive Disorder, Depression, Bipolar Disorder, Seasonal Affective Disorder)**

Mental health disorders become disabilities when they impact major daily life activities. They involve combinations of disturbed thoughts, emotions, and ability to relate to others, impairing daily functioning.

### Considerations when creating solutions for people with psychological/psychiatric disabilities:
*   **Provide applications to manage mood, stress, and anxiety**.
*   **Offer guided meditation options**.
*   **Utilise behaviour charts, point sheets, goal tracking, and positive reinforcement/rewards** to help with appropriate behaviour.
*   For **Anxiety Disorders**, which cause persistent fear or worry about certain situations or objects, leading to avoidance and uncontrollable reactions:
    *   **Panic Disorder** involves feelings of terror and impending doom, with symptoms resembling a heart attack.
    *   **Phobias** are strong, excessive fears of specific objects or situations (e.g., claustrophobia, arachnophobia, social phobia), which can trigger panic symptoms.
    *   **Post-Traumatic Stress Disorder (PTSD)** may occur after terrifying events (violence, war, natural disasters) and can cause nightmares, flashbacks, worry, anger, sadness, or guilt.
    *   **Obsessive-Compulsive Disorder (OCD)** involves perpetual upsetting thoughts (obsessions) alleviated by repeated intentional acts (compulsions).
*   For **Mood Disorders** (affective disorders or depressive disorders), which cause erratic changes in mood:
    *   **Depression** is characterised by prolonged sadness, loss of interest, feelings of worthlessness, or suicidal thoughts.
    *   **Bipolar Disorder** involves cycling periods of mania (high, happy feelings) and depression (low, sad feelings).
    *   **Seasonal Affective Disorder (SAD)** affects individuals during autumn and winter, causing depression due to shortened daylight.
*   For **Attention Deficit Hyperactivity Disorder (ADHD)**, which involves difficulty focusing, paying attention, and controlling behaviour, along with potential hyperactivity and impulsivity:
    *   **Minimise distractions** on web pages, as inattention can involve being easily distracted and difficulty organising tasks.
    *   Ensure **consistent, coherent, and predictable navigation** to help users stay oriented and follow pathways.
    *   Allow users to **control automatically updating content** and **set the refresh frequency**.
    *   **Limit interruptions** and make nonessential alerts optional to maintain user focus.
    *   Provide **options to pause, stop, or hide automatically moving, blinking, or scrolling content** (e.g., carousels, banners, animations, videos).
    *   **Break media into short, logical segments** with clear headings to help with focus and information retention.
    *   **Provide clear summaries and well-spaced text** with highlighted headings for long documents or web pages to help gather key points.
    *   **Avoid overwhelming users with too many options or complex information** to prevent cognitive overload, anxiety, and loss of focus.
    *   **Streamline processes and workflows** to include only minimally necessary steps and separate optional ones to reduce distractions and mental fatigue.
    *   **Provide information to help users complete and prepare for a task**, including time estimates and required resources, to help manage concentration and avoid mid-task distractions.
*   For **Personality Disorders**, where a person's behaviour patterns persistently deviate from cultural expectations (e.g., Antisocial Personality Disorder, Borderline Personality Disorder).
*   For **Eating Disorders**, which cause severe concern over food and weight, affecting eating habits (e.g., Anorexia nervosa, Bulimia nervosa, Compulsive/Binge eating).
*   For **Schizophrenia**, which involves hallucinations, delusions, lack of motivation, dreary mood, isolation, difficulty expressing oneself, attention/memory deficits, and trouble controlling movements.

## **Seizure Disorders (Photo-epileptic seizures)**

### Considerations when creating solutions for people with seizure disorders:
*   **Avoid creating animations, videos, and other graphics, that have flashing or strobe-like effects whenever possible**.
*   **If flashing content must be used, flashing should not last for more than three (3) seconds** and and should not flash more frequently than about 3 times per second. Using flashing, blinking, and flickering content that lasts for more than 3 times per second may trigger photo-epileptic seizures.
*   **Tools that may be helpful are flicker-free monitors, monitor glare guards, and non-glare glasses**.
*   Be aware that seizures can be caused by brain injury, dehydration, sleep deprivation, infections, fevers, drug overdoses, drug withdrawals, or even flashing lights. Not all people with seizure disorders are sensitive to flashing lights, but web designers should avoid them to prevent possible injury.

## **Speech Disabilities**

Speech disabilities involve difficulties articulating words, producing or organising speech sounds/syllables correctly or fluently, or a total loss of voice. These can include stuttering, cluttering, apraxia, dysarthria, speech sound disorders, and muteness. Causes can be generic or linked to other disabilities like learning disabilities, auditory disabilities, autism, traumatic brain injury, stroke, and cancer.

### Considerations when creating solutions for people with speech disabilities:
*   **Provide text-based alternative solutions such as chat, email, and forms for voice-based technology tools like virtual meetings**.
*   **Ensure that all digital content is compatible with several assistive technologies, such as screen readers**, especially if another disability (hearing loss, fine motor movements, processing information, visual impairment) is present.
*   **Provide captions and transcripts for video and audio materials**.
*   **Check that digital content is keyboard accessible**.
*   **Present information in multiple formats to assist with information processing**.
*   For wheelchair users or those with difficulty using hands/arms, apply **the same solutions as for motor disabilities**.
*   For general difficulty producing speech sounds:
    *   May use **low-tech Augmentative and Alternative Communication (AAC)** such as communication boards or gestures to supplement speech.
    *   May use **high-tech AAC** such as computer-generated voices to replace speech.
    *   **Be patient and give people time to communicate thoughts**; ask for clarification if necessary.
*   When designing input methods, follow the **same input design considerations as for blindness, low vision, motor disabilities, auditory disabilities, and cognitive disabilities**. Ensure text-based alternatives are provided for any voice-based communication methods.
*   Output design considerations are also **similar to those for blindness, low vision, motor disabilities, auditory disabilities, and cognitive disabilities**.