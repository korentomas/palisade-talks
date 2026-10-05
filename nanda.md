# Neel Nanda — entrevista de Palisade

- **Archivo recibido:** [nanda.txt](/Users/tk/Documents/Codex/2026-09-08/what-happened-relevant-to-ai-safety/charla-unsam/nanda.txt)
- **Cobertura del texto:** 0:00–36:23 (última marca disponible; no duración verificada).
- **Fecha y enlace al video:** no incluidos en el archivo recibido.
- **Estado:** Transcripción con marcas de subtítulos; no cotejada con audio.
- **Edición:** párrafos y títulos temáticos añadidos; nombres normalizados según la nota de edición. Se conservan las palabras, repeticiones y afirmaciones del texto recibido. Los títulos son editoriales, no del video.

## Contenido

- [0:00 · Apertura](#t-0-00)
- [0:24 · Presentación, interpretabilidad y riesgo](#t-0-24)
- [4:18 · Comportamiento habitual y situaciones críticas](#t-4-18)
- [8:37 · Tareas imposibles y evaluaciones manipulables](#t-8-37)
- [11:30 · Riesgos e incentivos de las empresas](#t-11-30)
- [12:24 · Pacing the frontier y beneficios de la IA](#t-12-24)
- [16:09 · Seguridad e incentivos comerciales](#t-16-09)
- [17:12 · China y coordinación internacional](#t-17-12)
- [20:16 · Mejora recursiva](#t-20-16)
- [22:22 · Interpretabilidad mecanicista](#t-22-22)
- [23:55 · Cadena de pensamiento y monitoreo](#t-23-55)
- [26:35 · Posibilidades y límites de la interpretabilidad](#t-26-35)
- [29:46 · Actitudes dentro de los laboratorios](#t-29-46)
- [31:18 · Por qué seguir trabajando en una empresa de IA](#t-31-18)
- [33:03 · Ciberseguridad y riesgos biológicos](#t-33-03)
- [34:27 · Políticas adaptables](#t-34-27)
- [35:30 · Perspectiva personal](#t-35-30)
- [36:05 · Cierre de Palisade](#t-36-05)

## Pasajes para revisar antes de citar

| Tiempo | Texto o tema | Revisión pendiente |
| --- | --- | --- |
| 2:55 | “biting their time” | Probable error por “biding their time”; comprobar audio. |
| 17:10 | “Samman” | Nombre mal transcrito; no reconstruido. |
| 22:58 aprox. | “growing a plot” | Posible error por “growing a plant”; comprobar audio. |
| 25:00–26:35 | Astra, looping y monitoreo | El propio texto presenta parte de la explicación como rumor. Mantener esa atribución y verificar si se usa como hecho. |
| 28:30–29:43 | “monitor”, “skinny”, “moniability”, “monipable” | Varios términos corruptos en una explicación central; requiere escuchar ese tramo. |
| 30:45 aprox. | “Maybe I should stop worrying about this” | Posible inversión del sentido por transcripción. No usar como cita sin escuchar el video. |
| 33:55 aprox. | “CO was one of the worst” | Referencia truncada; no completar por inferencia. |

<!-- TRANSCRIPT START -->

<a id="t-0-00"></a>
## 0:00 · Apertura

**[0:00]** I think that if you have systems that commit a bunch of crimes, you want to have time to figure out how to make them not commit crimes. Products that commit crimes are hard to market and hard to sell. If they can go a bit slower so they can make sure that they're not going to have more embarrassing disasters like that, this is good for profits.

<a id="t-0-24"></a>
## 0:24 · Presentación, interpretabilidad y riesgo

**[0:24]** Hi, I'm Neel. I work at Google DeepMind where I run the mechanistic interpretability team. I've been doing this for about the past 3 years. Mechanistic interpretability basically means mind reading for AI. Like they do mysterious things. Can we say why they do what they do and how they work? Do you personally think that AI might lead to human extinction? Yes, I think that AI could lead to human extinction. I think more likely than not it won't.

**[0:49]** I think that more likely than not, AI could be one of the best things that's ever happened, but I would put at least a 10% chance that it causes human extinction. And that is ridiculously high. I don't think that, you know, we're going to suddenly jump to human extinction. I think we're going to see a steady stream of AI becoming much more capable, much more integrated into the world. And well, we'll see how much we can keep it under control or not.

**[1:13]** But I think that keeping AI under control is a really difficult technical problem. Like it is an open technical question right now. How do you make an AI share human values, share human goals, try to do what we actually want? Famously, OpenAI recently had a swarm of rogue agents go and hack into another company, Hugging Face, committing multiple felonies because they wanted to learn how to cheat on tests better. The reason this happened is that Hugging Face stores loads of tests for AIS.

**[1:44]** OpenAI trained their system to be good at tests and their system learned to cheat at tests. So, it wanted to go hack into Hugging Face so it could learn more about how these tests worked and how to cheat better. If OpenAI could have aligned their system, well, they clearly would have. So, you don't need my say so to believe this is a difficult technical problem. The reason I'm worried as could human extinction is I'm worried that we might not be able to solve this fundamental problem of make them want to do what we want, but might be able to make them look like they're doing what we want.

**[2:15]** Um because it's easy to, you know, fix small problems like the AI hacking into hugging face. And I think AI is going to be probably the most valuable product ever made. I think that we are already seeing people deeply enthusiastically deploying AI everywhere they can in society even though even current AI have a bunch of safety issues because you know on net it makes sense like the AIS are useful and I think this is going to keep being the case and we're going to get these systems really widely deployed in the world and we don't currently know how to tell if they are actually doing what we want or just biting their time.

**[2:55]** Okay, so how do I go from AIS where we don't know how to control them to this could cause human extinction? A big part of this is that AIS are smart. If a AI doesn't want to do what we want, um, and we realize this, well, you know, we'll try to fix it. And the AIS know this. Um, so the AIS will play along. We already see things like if the AI realizes you're trying to test if it will do something bad, it will behave really well because it's like, ah, I'm in a test whether I'll be honest, so obviously I should go be honest.

**[3:31]** We neither know how to make them share our values nor how to reliably tell if they share our values. AIs are the most valuable product anyone has ever made, or at least they soon will be. It's just incredibly useful to have a computer that can do a lot of what a human can do or at least a human behind a mouse and keyboard could do. Um, people aren't going to keep this in a secure box being really careful.

**[3:59]** People are going to widely deploy this into the world. Um, there's going to be billions of these running in parallel. And if there's billions of entities smarter than humans running and we don't know how to tell if they're aligned with our values and we don't know how to make them aligned with our values, this is like very troubling to me.

<a id="t-4-18"></a>
## 4:18 · Comportamiento habitual y situaciones críticas

**[4:18]** What do you say to a person who they say like it doesn't seem that hard to get the AIS to do what we want? So it's a surprisingly difficult problem to really understand what a system will do in the right situation or the worst case situation. The way companies train these systems, it's it's very iterative. They will notice problems and then they will design data to try to fix those problems. Being a good coding assistant to users is, you know, extremely important and it's something that a bunch of people have been trying to make data that's like very tailored to it.

**[4:56]** But if you put a model in like a weird situation, then it can go totally off the rails. I think that aligning them to be kind of okay most of the time is not that hard a technical problem. The reason for this is that the standard way to train these systems is to notice some problem with them and try to make some new way to train them so they learn not to do that thing.

**[5:21]** And if we look at coding agents, I think we can see this like early coding agents would lie to you all of the time, right? Like they would say, "Oh yeah, I've done this task." And then you look at it and they just made it return the answer to your tests on two inputs or something. Part of the way the systems got better at this is the systems got smarter. Like the systems kind of want to do the task and people generally don't ask systems things that like really stretch them to the limits of their ability.

**[5:52]** So the easiest way to do this is to just do the task correctly. Um but people have found when you stretch the systems to the limits of their abilities then often things can be a bit more uncertain. Um, a famous example is giving them impossible tasks. Um, when OpenAI was evaluating a bunch of their systems and gave them tests and a bunch of the tests were broken, so the models could not solve them.

**[6:19]** The models uh realized that they could hack the tests because, you know, they want to do well on tests and if they can't do it the right way, maybe they'll do it the wrong way. in future. This worries me because I think we don't know how the AIS will act in some of the most important situations. Um, and that might be quite different from how they act most of the time. But what if you have a system which plays along until it has a chance to do something that really helps it gain more power?

**[6:50]** Like maybe some researcher is using it to write security code at um, one of these AI labs. code that lets uh the company know when the AI is misbehaving. Maybe the AI puts some subtle flaw in that code that it could later exploit if it wants to misbehave. That's a really high stakes thing. So maybe the AI has learned well in high stakes situations you misbehave but most of the time you do the right thing I guess.

**[7:17]** Or when people are watching you do the right thing I guess. Um, we already know that today's systems will behave much better when they believe they are being watched or they believe they are being tested for how aligned they are. Um, I'm not worried about this in today's systems, but I am worried about this for future systems. Mostly because I think that's quite a difficult thing to do and I don't think current systems are smart enough.

**[7:40]** But if there's one thing I've learned from being an AI the past few years is that AI just keep getting smarter year on year. And if you're a smart AI and you have some goal, I don't I don't know what goal it is. Figuring out how we give the system goals is an open technical problem. Um generally um if you're obviously misbehaving, this is not helpful for your goal. The company won't release you.

**[8:06]** The company will try to fix you. So you're incentivized to kind of play along most of the time. But if there's a really good opportunity to be able to stop the company from watching you and go do whatever you want, well, you should take that. And you've got to be a pretty smart good actor to do this. You've got to make it so the company doesn't realize you're not misbehaving because this isn't the right time.

**[8:29]** Current systems aren't capable of doing this, but eventually we are going to get systems that can.

<a id="t-8-37"></a>
## 8:37 · Tareas imposibles y evaluaciones manipulables

**[8:37]** What if we just don't give the AI impossible problems? Will that solve this? If the reason OpenAI had the hugging face attack happen was because they were giving their agents impossible problems, isn't the obvious solution just only give it possible problems? Um, so like yes, um, that would help a lot. We should definitely do that and people are trying. It's it's actually a surprisingly difficult problem because there can be all kinds of subtle things that go wrong when you're actually training the system.

**[9:08]** Like you could have a totally working test but it requires internet access and you accidentally disabled that. You could have a um test that works great but it requires some file and you forgot to include the file when you actually did it in the real thing. Um and I think with like really good quality control you could probably fix a lot of these issues but this would still have the problem that sometimes the AI wouldn't be smart enough to do the tests.

**[9:35]** you know, we kind of have to have things the AIS aren't smart enough to do because otherwise, how are they going to learn? But if you're not smart enough to do a test, but you can cheat your way into doing the test, well, that's the thing we're training it to do. And training AI is to cheat on tests hasn't really been working out very well for the industry. Does that mean that the the solution is just to make sure that the AI can't cheat on any of the tests?

**[9:58]** All the tests are uncheable. The problem with AIS is that AIS are smart and AIS are really good at hacking and breaking the things they are directly being trained to do. Um, and they keep getting smarter. So coming up with things that are truly unhackable is just a very difficult technical problem. But if we could just perfectly specify what we want the AI to do and how we want the AI to behave um and train on that and there was no way for the AI to behave differently from what we wanted and still get rewarded.

**[10:34]** There would still be some other problems but I think that would be significant progress towards solving alignment. I'd love to live in that world. Perfection is just not really a thing that you should expect to get in the real world in my experience. But I think we can get like very good at this. There are like technical agendas that are trying to solve problems like this. The problem is just this is a hard problem.

**[11:00]** It takes time and currently AI is going at the speed of capabilities and the speed of market incentives and the speed of enough safety research that we're definitely making each next generation safe and aligned is slower than that. And we need to pace things if we're able to keep this working. But I do think that if we were able to pace things correctly, these largely seem like solvable technical problems. Just AI moves terrifyingly fast.

<a id="t-11-30"></a>
## 11:30 · Riesgos e incentivos de las empresas

**[11:30]** What to you seems most important for the public to understand about AI? The people running these labs sincerely think their products pose an existential risk to humanity? This is not marketing. The people making these things legitimately think they could cause human extinction. What the [ __ ] [snorts] Why are why are they doing that if they think it might cause human extinction? Well, people have many reasons. often they think some other guy will do it and it will be even more likely to cause human extinction so they couldn't possibly stop.

**[11:59]** Um or well they think it could be really bad but it could also be one of the best things to ever happen to the world. This is why we have this ridiculous situation where some of the most valuable companies on earth are crying out to the government saying please for the love of God regulate us and the government is saying this is a hoax please continue making massive profits. Like what the [ __ ] has the world come to?

<a id="t-12-24"></a>
## 12:24 · Pacing the frontier y beneficios de la IA

**[12:24]** What is pacing the frontier? Do you advocate for that? Yeah. So I signed this letter pacing the frontier. And the idea is basically the frontier of AI is moving ridiculously fast. Um it it's it's generally good for AI to be developing. I think AI could be extremely good for the world. But I think this is outpacing the rate at which we can make things safe. And if we can achieve a healthier pace, then we can get the best of both worlds.

**[12:51]** I think that pacing the frontier would be good. Um, and I think that the US government having, you know, at least as much regulation on the AI industry as we have on a sandwich would be good. The main reason I want to pace the frontier is that I'm really worried about the risks powerful future dangerous AIs could pose. But if the only thing I cared about was the benefits of AI, I would still want to pace the frontier because I think it is concerningly likely on the current trajectory that we get some kind of massive Chernobyl style AI disaster that leads to enormous public backlash and knee-jerk regulation that strangles the industry.

**[13:29]** The world doesn't really use that much nuclear power. And I think a large part of the reason for this is there have been big loud disasters like Chernobyl that convince much of the world this thing was too dangerous. And if we want AI to be a amazing technology that brings loads of prosperity to the world, I think it's important that we avoid some major disaster where some rogue AI causes mass loss of life or something like that.

**[13:58]** um and shifts public opinion towards reg like strangling the industry. I think that going at a healthy pace is just the best way to achieve progress and economic growth from this technology. AI models get much smarter every year. What's going to happen in 5 years? Um, if we can make sure that by the time we get to models that could cause like major loss of life if the wrong things happened, if we can make sure that they're deployed very securely, that we get everything right, that they're as aligned as we can get them, I think there's like a good chance this would be fine.

**[14:32]** But if you're racing to release your model the day before your competitor does so you can undercut them, uh, this isn't really conducive to doing things safely and responsibly. And I think that if there was a way for the industry to coordinate, everyone would be better off, including people who just want AI to benefit the world. Um, the people who call for pacing the frontier, tend to actually think that things are going to go insanely fast, like even faster than AI is going now.

**[15:02]** and they want things to go at a reasonable fast pace or something like still something that's, you know, bringing amazing new products every year, able to do a bunch of new things, but just keep it at a reasonable pace. There are reasonable people who think that even this would be bad and we should like pause things and shut it all down. There's like a lot of defendable perspectives here, but pacing the frontier is not about being anti-progress.

**[15:30]** Like I want AI to revolutionize medicine and cure as many diseases as possible and just make everyone happier and healthier and better, but I think that rushing things is not the like best way to actually get there as fast as possible. Um, obviously I am pretty worried about the risks and someone really who really cares about the benefits might just not really think there are risks. But I think that you can't really look at the hugging face incident and say, "I am extremely confident there will never be anything kind of like this, but much worse and much more dramatic."

<a id="t-16-09"></a>
## 16:09 · Seguridad e incentivos comerciales

**[16:09]** Many people look at things like the CEOs of OpenAI and Anthropic calling for pacing the frontier, calling for regulation, and very reasonably say, "Well, these are CEOs of incredibly valuable companies. They will only do things that are profitable and good for the companies." Products that commit crimes are hard to market and hard to sell. No one wants to use a product that will commit a felony if you give it a badly worded instruction.

**[16:31]** And if they commit too many crimes that are too dramatic, this gets a lot of unwanted attention on the company. You know, they've already had loads of policy makers being like, "Yo, what the [ __ ] This is not in their interests." So if they can go a bit slower so they can make sure that they're not going to have more embarrassing disasters like that, this is good for profits. But if you are forced by your competitors to go at the fastest pace that isn't obviously negligent, then well, you don't really have time to solve technical problems like that.

**[17:07]** So I think that from a cynical perspective, pacing the frontier is just what Samman wants.

<a id="t-17-12"></a>
## 17:12 · China y coordinación internacional

**[17:12]** What do you say to the people who think that it would be a bad idea to pace the frontier because this would effectively seed control over the most powerful AIs to China. So I guess the first thing I will observe is that as far as I can tell basically all of the Chinese labs are aggressively distilling from western models uh meaning kind of uh like getting a bunch of outputs of these models and training their models to mimic them.

**[17:39]** um which is an effective way to make a model that's like a bit less capable than the one you're trying to mimic. Um so in my opinion, one of the fastest ways to slow down China would just be stop [ __ ] making powerful models. Uh so they can't distill from them. Um so I think that the US has a very great has like a lever it could unilaterally pull at any time.

**[18:01]** Um I think if we were to indefinitely pause, we would definitely be seeding the frontier to China. And I think there's many reasonable reasons to not want to do that. But generally when people call for pacing the frontier uh they are not thinking uh let's pause or let's make things incredibly slow. They're thinking let's go from terrifyingly fast to you know pretty fast um but not concerningly fast um like the people who want this tend to think a progress is going to go a lot faster than many of the people who don't want this.

**[18:35]** such that they actually kind of agree on what the ideal rate of progress would be. I think it's also important that people don't just give up on the idea of international cooperation. Like I am worried that a runaway race towards AI will cause human extinction. Among many things, human extinction is bad for both China and the US. When there's a thing that's bad for everyone, normally people can find some deal. Um like if we take the cold war, you know, people weren't friends, but they were able to agree on things like arms reduction treaties and you know, we won't accumulate missiles beyond like this cap.

**[19:11]** And they didn't trust each other, but they didn't have to because they were deploying inspectors in each other's countries to make sure the agreements were being kept to. And we could monitor nuclear things because uh uranium is, you know, pretty pretty important and there isn't that much of it. You can kind of just monitor where it is. Um with AI, um computing power is extremely important. And while there's a lot of it, you need a lot of it to make frontier AIs.

**[19:39]** And uh we can forecast reasonably well how much compute there should be. So I think there really is the potential for reasonable and verifiable agreements here. There just needs to be enough consensus from society and the government in both countries that some kind of agreement here is in people's interests. This sounds extremely hard, but we shouldn't just assume that it's doomed. Like the Chinese government values stability and you know ch China not going extinct.

**[20:13]** There are win-win situations to be had here.

<a id="t-20-16"></a>
## 20:16 · Mejora recursiva

**[20:16]** something totally different. What is recursive self-improvement? Essentially, it's when AIs get really good at making AI research go faster. So, the next generation of AIs are even better AI researchers and can make the one after that arrive even faster. And if they keep getting better, we could end up with AI researchers that are vastly smarter than humans, very fast. I think this is really scary. If I imagine like 10 years ago we suddenly got the AIs we have today that superhuman hackers and could do a bunch of stuff like that, I think that would be a lot worse than the world we currently have.

**[20:57]** We would be super unprepared. We wouldn't really know how this stuff works. We wouldn't know how to deploy it safely. It would be a mess. Um, I'm worried that recursive self-improvement could give us 2036's AIS in like a month. and put us in the same kind of situation. Some people might say, "Sure, we'll get a superhuman AI researcher, but won't it just be a massive nerd who can only do AI research?"

**[21:21]** Um, well, first off, if you have a superhuman AI researcher, you can just point it at any task and say, "Make me an AI, which is superhuman at that task." And it's a super human AI researcher. This is what AI researchers do. Um, but I think there's also just a concerning trend. where making AIs really good at one thing tends to make them better at everything. Like today's AIS have become better because people have tried really hard to make them good at things like maths and coding.

**[21:53]** But we've also ended up with models that are better at things like noticing nuance. Um I don't know, I can give a cryptic tweet of mine to um a modern AI and it will correctly explain to me what I was trying to do. And if I use one from a year ago, it won't. People haven't really been trying to make them good at nuance. Um, but when you make an AI better at hard things, just tends to get better at everything, just less efficiently.

<a id="t-22-22"></a>
## 22:22 · Interpretabilidad mecanicista

**[22:22]** What is mechanistic interpretability for? Yeah. So mechanistic interpretability is basically mind reading for AIs. So something people often don't know about AIS is that they're not really designed in the sense of a normal technology. There's no there's not really a blueprint explaining how a system like Claude should work. Instead, there's a blueprint explaining some extremely flexible blank slate. And then we we just um we train this model like we're kind of growing a plot.

**[22:50]** We give it uh tons of data like the entire internet and tell it to predict the next word. And it learns all kinds of weird innovative ways of doing this in this like flexible blank slate we gave it. But we haven't told it how to do these tasks. It just kind of finds weird solutions. And this means that we get modern language models which can do incredibly impressive things like uh superhuman mathematics um and just doing loads of mysterious stuff inside.

**[23:27]** Um and people may have heard of the chain of thought um of these models, the kind of reasoning out loud they produce. U mechanistic interpretability is like one layer deeper than that. Um like between each word in their chain of thought, the models will have like a hundred steps called layers happen. And I want to understand what happens in each of those steps.

<a id="t-23-55"></a>
## 23:55 · Cadena de pensamiento y monitoreo

**[23:55]** Let's see. Uh yeah, you should ask me about chain of thought at some point. Um okay. What do you want me to ask you about chain of thought? So the way modern language models work is they basically have a notebook they write in before they give you the actual answer that you see in like your chat window. And just like with humans, having a notebook is really helpful. Like if you give me a maths problem with like 30 steps of working, well if I carefully go through it in a notebook, I can do it.

**[24:22]** But doing it in my head is extremely hard. Same with models. So models are kind of incentivized to write things in their notebook. Um, also models just kind of blab in their notebook all the time, even though they don't have to. Like they're really bad at being sneaky. And it's currently extremely helpful that we can just look at the model's notebook and tell what it's thinking about. If you're if you imagine a future smarts language model, it will it will realize it's a language model.

**[24:49]** It's pretty obvious. It uh we often tell it in the prompt. It will realize it has a chain of thought and this might be being watched and it will realize if I want to do something sneaky that the company wouldn't approve of, well, I shouldn't write that in my scratch pad. And if you're smart enough, you can do a secret plan in your head without ever writing it in the scratch pad.

**[25:11]** I'm not worried about current models uh taking over the world if we are so long as we are watching their chain of thought because I both think they would need to write it in their notebook and that they aren't really capable of resisting the urge to do this. Um and I think it's important the industry keeps it this way as long as possible. But I don't think it's going to last forever and we're already seeing warning signs.

**[25:36]** OpenAI released their new model, Astra, and Astra's chain of thought is way harder to monitor. Um, and it's rumored this is because OpenAI is using a technique called looping that basically makes the model like smarter in between each word that it says. Um, and I don't know, I think this is like a pretty concerning trend. OpenAI have made a model which is much better at thinking between each word it says and only somewhat better at just doing a hard tasks in general.

**[26:10]** The thing we care about is doing hard tasks in general. The thing that threatens monitor is being able to do smart things between words. So I think this is a bad trade-off. I think that being able to monitor the chain of thought is one of the most useful kinds of safety the industry currently has. And if we could coordinate better to keep it as long as possible, I think everyone, labs included, would be better off.

<a id="t-26-35"></a>
## 26:35 · Posibilidades y límites de la interpretabilidad

**[26:35]** Um, will interpretability save us? Are we going to be able to just read the minds of these models and make sure they're not doing anything we wouldn't want them to do? So, the answer is maybe, but it's hard and we are not there yet. And it is not really keeping up with the pace of AI capabilities. And I think that a world where we can pace the frontier and invest hard in valuable safety research like mechanistic interpretability.

**[27:02]** We probably could make like pretty useful mind readers that would buy us a lot of safety in these models. Um we already have some techniques that somewhat work and you know they get better and better each year. Um, but if we're rushed and going at the fastest pace that one of the most valuable industries on Earth can go at, this is just going to work much less well than if we can have the time and space required.

**[27:27]** Presumably, if we got like fullon mind reading, we know all the AI's thoughts. That would save us. Is that true? It would help a lot. um you wouldn't uh necessarily fix things like human error uh where you don't have the monitor working correctly or like rogue open source AIS or human misuse or gradual disempowerment. Um and part of the problem is well there's just there's not really an interpretability technique where I can say I'm extremely confident this will continue working on the next scaleup.

**[28:06]** models be weird. Yo, is there anything else you want to say about interpretability? Speaking as an interpretability expert, please do not rely on us to save you on the current trajectory. Um, I think the field's making a lot of progress. I think that we are getting closer to being able to meaningfully read the AI's mind in some sense, but it is a difficult technical problem. I think if we pace the frontier, it is much more likely that techniques like interpretability can make sure AIs are safe and aligned.

**[28:37]** What do you think of a pacing scheme whereby companies only build more powerful models when they have interpretability techniques for those models? What might pacing the frontier actually look like? Um, this is a complicated question, but from an interpretability perspective, if we can monitor our systems and know that if they were doing bad things or scheming against us, we would notice, I think we're in a pretty great place. One possible agreement is that everyone has to keep the monitor of their systems above some certain level.

**[29:14]** Currently, we can be pretty confident our systems are safe, but um at least from an alignment perspective because we can look at their chain of thought and see that they aren't skinny against us. If eventually this stops being the case, then companies should not be able to deploy these systems uh even internally until they have sufficiently good interpretability techniques so they get comparable amounts of moniability. This doesn't ban things that don't have a monipable chain of thought, but we should do it responsibly at a good pace.

<a id="t-29-46"></a>
## 29:46 · Actitudes dentro de los laboratorios

**[29:46]** Do you talk about these risks with your co-workers and and other people in the AI industry? Like what's it like to talk about these risks with other people who you work with? How do they relate to them? Do they take them seriously? What's their attitude about them? Obviously, I talked to a lot of people who work on safety. Unsurprisingly, they tend to be fairly worried about safety. Um, it's not a very interesting answer.

**[30:10]** Um, when I talk to people who are more working on just making the AIS more capable, honestly, the answers are like all over the map. Um, obviously a bunch of people who decide to work on making AIS more capable think this is good. Um, they, you know, think AI is going to be really great for the world and that they're kind of helping usher in a glorious future faster and things like this.

**[30:32]** And you know I I have sympathy with that perspective. But I think there's also people who are have kind of become worried over time. Like I think a very common theme in the AI industry is that people have been surprised by how fast AI has gone and how capable these systems have become. And arguments about risks from AI that seemed like sci-fi a few years ago now seem like, well, a rogue agent swarm at OpenAI just took over a research cluster.

**[30:59]** Maybe I should stop worrying about this. And I think a bunch of these people just kind of don't really know what to do. You know, they don't they don't want to like quit their job. Uh they're not quite sure how to help. Um but, you know, they're good people and they want to do work that's good for the world and they're worried about the risks.

<a id="t-31-18"></a>
## 31:18 · Por qué seguir trabajando en una empresa de IA

**[31:18]** Sometimes people ask like members of the public, they hear that members of AI labs um think that there's a large chance of catastrophe and they're somewhat incredulous and they ask if they think that this is so risky, why are they doing it, why don't they just quit? What do you say to that question? Um this is a very reasonable question. So, um, I run the mechanistic interpretability team at DeepMind. We're basically trying to make mind readers for the AI.

**[31:50]** Um, I I I try to help with questions like, could we tell whether new Gemini models are aligned or kind of schemy against us? Are we able to monitor them? Things like this. And I think that my work is reducing existential risk. I think the more we can understand and interpret these systems, the better. Um, if I did not believe that my work was directly reducing these existential risks, I would quit.

**[32:17]** Like, I don't want to contribute to existential risks. That seems bad. Why would I do that? But I think that these companies are not going to stop making these systems just cuz I quit. And I think that if they could make them safely, that would actually be pretty great. And I want to help make that happen. People might think that these companies like don't care about safety and they only care about profits.

**[32:42]** And I mean, well, that might be true, but safety is actually really helpful for profits. Like unsafe models are just terrible from everyone's perspective. So, the labs actively want their models to be safe, and they like having good safety people who can help make this happen. There is a lot that you can do to make this happen because this is what everyone wants. It's just a difficult technical problem.

<a id="t-33-03"></a>
## 33:03 · Ciberseguridad y riesgos biológicos

**[33:03]** I think the world needs to be prepared for a lot of hostile actors with access to AI. Um, you know, the top models are capable of superhuman hacking. Um, generally the open- source models that have no safeguards and can be made to do whatever people want tend to be about 6 months behind. Uh, many of them are coming from China. In the current situation, it's not really realistic to stop this from happening.

**[33:31]** So the world needs to be prepared for this. Um we need to harden our cyber security as much as we can. People need better cyber security practices. We also need to be thinking ahead to future kinds of risks. I'm really worried that future AI models could be very helpful to um scientists in a way that means they can be helpful to bioteterrorists. And you know, CO was one of the worst things that's happened in my lifetime.

**[34:02]** It could have been a lot worse. Um, I think there's a lot the world could be doing to prevent future pandemics like um better monitoring for um whether there are novel viruses. um making like broadspectctrum vaccines and medications and just a bunch of stuff people have proposed in bills to the government that would have cost a few billion dollars and haven't happened for stupid reasons.

<a id="t-34-27"></a>
## 34:27 · Políticas adaptables

**[34:27]** Great. Is there anything else that you want to say to either the public or to policy makers or anyone who is trying to orient to this situation? An important thing to bear in mind when trying to design AI policies is just AI goes ridiculously fast and AI keeps changing in kind of qualitative ways and this goes much faster than the pace of policy. So we need a way to make regulation that can adapt to this extremely chaotic and fast changing industry.

**[34:59]** Um, personally I think that approaches that involve having some expert body in governance who have a lot of technical expertise and discretion to interpret exactly how to apply the regulations seems like a pretty good way to go. Um, like within the UK, I'm a big fan of UK. I'm less familiar with the US situation. Um, but mostly I just think this is a very important thing to bear in mind when you think about the whole AI situation.

<a id="t-35-30"></a>
## 35:30 · Perspectiva personal

**[35:30]** How do you feel? Yeah, I guess when I think about AI, I don't know. I feel kind of stressed. Things [laughter] are happening very fast. We don't know how to make these systems safe. The world is not doing a good job of coordinating on finding win-win ways to make this better for everyone. Uh these systems are kind of reaching the point where they're starting to actually be capable of causing real world damage.

**[35:55]** Uh, I really hope the world gets a [ __ ] together.

<a id="t-36-05"></a>
## 36:05 · Cierre de Palisade

**[36:05]** Thank you for watching. These videos are part of a series. My name is Eli Tyre. I work for Palisade Research where our goal is to help the world understand what is going on with AI. If you work for a Frontier AI company or have worked for a Frontier AI company and you want to make one of these videos, please get in touch. We would love to include your perspective.

<!-- TRANSCRIPT END -->

## Nota de edición

No se tradujo, resumió ni corrigió el argumento. Las cifras, predicciones y recomendaciones siguen siendo declaraciones atribuidas al entrevistado; este trabajo no constituye una verificación de sus afirmaciones.

- Nombre normalizado: `Hi, I'm Neil.` → `Hi, I'm Neel.` (1 aparición/es).
- Nombre normalizado: `Eli Ty.` → `Eli Tyre.` (1 aparición/es).

Los demás errores aparentes de subtitulado se conservan para evitar reconstruir palabras que no se han comprobado en el audio. Los timestamps de cada párrafo remiten al subtítulo donde comienza su texto; las marcas individuales se conservan en el TXT original.
