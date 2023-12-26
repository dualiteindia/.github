# Dualite Plugin - User Documentation

## Version Update - beta_v3

Dualite is a powerful tool that seamlessly converts Figma interactive designs into code, pixel-perfect, providing developers with a streamlined workflow and reducing the time and effort required to bring interactive and animated designs to life.
<br><br>
The following documentation highlights the best practices and the things to be cautious about utilising the tool to its maximum efficiency, ensuring optimal results while keeping in mind its current capabilities and upcoming features.

## Overview

Our tool converts static Figma design to React and HTML/CSS to an almost pixel-perfect extent. Our tool supports various types of linear Frame-to-Frame prototyping interactive prototyping Figma flows, enabling you to get code for static as well as dynamic user experiences built on Figma.
<br><br>
For either type, you just need to start by selecting the Static Frame or the Starting Frame of the flow(Interactive Prototype). For Static Designs, you get the option of copying the HTML/CSS. If you’re converting an interactive prototype into code, you'll also get animation scripts (javascript) that'll be responsible for animation's control flow.
<br>
<br>
You can just copy & paste the generated code in your project.
We’ve also provided a direct **_‘Preview in Code Sandbox’_** option that lets you skip the copy-paste effort and directly makes you preview the result as well as the encompassing code.

## What's new in beta_v3

- React and HTML conversion, both with Vanilla CSS.
- Figma Prototypes (even complicated ones) to CSS Animations (KeyFrames).
- Figma Dev Mode support.
- Optimized image conversion process and internal algorithms, that has reduced the conversion time by almost 5x.
- Optimized Linear prototyping to CSS animations logic.
- Overall faster conversions in beta_v3, compared to beta_v2.
  <br>[Speed and efficiency comparision graph between beta_v1, beta_v2 and latest beta_v3] <br>
- You can now report issues and give us your feedback on this github repository.
- Improved new UI.
- Bug Fixes. Some commonly faced issues with Instances have been fixed along with some other issues found in internal testing and user feedbacks.

## Things to keep in mind (for designers)

As designers, there are some minor changes and guidelines, which will make the generated code much better and easily integratable. Here are some tips.

## Using the generated code (for developers)

Here we'll be discussing how you can use Dualite for production applications or you next personal project.

## Future Updates

We're here with a long term vision.
<br>[issues list]<br>

#### Faced anything other than mentioned above? Tell us now by raising an Issue [here].

## Want to know how we do it?

1000+ commits <br>
20k+ Lines of code <br>
4 developers (and their blood) <br>
and countless hours of brainstorming<br>

this has made Dualite, the fastest evolving Indian Figma plugin.
<br>Let's get you a sneak peak of how exactly Dualite works internally.

### Technology

We use TypeScript, React.js, Redux and esBuild for the plugin and Next.js, React.js, Firebase, Express.js, MongoDB and AWS for essential services.

### Architecture

We have developed a modular & scalable structure that allows us to easily add new features and framework support. The language independent processing is done seperately, after that our language/framework modules kick in based on user selection. This new architecture has improved our internal efficiency, enabling us to deliver better and faster updates in future.

## Want to share your thoughts?

Add an issue with "feedback" label here, or mail us directly at info@dualite.in
