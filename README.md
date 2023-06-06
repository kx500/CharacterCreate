1、
After installing Character Edit, we open the demonstration level and try running it

CharacterCreate ->Demo ->DemoMap

If there are no accidents, it should be able to operate normally

2、
How to apply to existing projects?

Open CharacterCreate ->Demo ->BP_ We can see from GameMode that the widget EditVisage was called, and several parameters need to be passed in when constructing EditVisage:

Gender: Role Gender

PreviewCharacter: Demonstrate character objects (character seen in the viewport)

IsDevelop: Developer mode (this is mainly used to generate various thumbnails, such as adding a new hair, which can be used to generate a preview image of the hair through the Development mode)



You can refer to CharacterCreate ->Demo ->BP_ GameMode internal methods
