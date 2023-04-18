You can see that for this when I hit enter here right after this arrow ->
This sentence will continue on the same line

But what if I want a newline with the extra space between 2 sentences but still keep them
as a paragraph, I guess the computer/file/program already formats that for me

wow

uiy
i

iuy

## Near-Search Algorithm: ##
In the case that Best-Search and Ideal-Search algorithms fail to find a room for a given group 

For example: a group of 4 cannot be assigned anywhere because all 4 person rooms across campus are filled.

The Near-Search algorithm will then split the group up (utilizing python list slicing) to split the group up into 2 smaller groups then tries
to find to 2 rooms within the same building to assign each group to.

Like the groupSearch algorithms, the nearSearch als has an best and ideal version

### Ideal vs Best: ###
Ideal takes into account the group's building preferences when finding rooms to a specific dorm 
while best does not take preferences into account and will try to find 2 rooms that are free within any building on campus

## Split-Search Algorithm ##
In the case that Best-Search and Ideal-Search algorithms fail to find a room for a given group 

For example: a group of 4 cannot be assigned anywhere because all 4 person rooms across campus are filled.

The Near-Search algorithm will then split the group up (utilizing python list slicing) to split the group up into 2 smaller groups then tries
to find 2 rooms that are connected via a bathroom (since in essence it will be a "group size" room) within a building to assign each group to.

## Things to note: ##
Currently we are thinking that *split* comes before *near* since the group will still be together in *split's* case, but if that fails to assign the group a room,
then *near* will at least try to put the splitted-up group in the same building at the minimum keep the group close together in the same building

