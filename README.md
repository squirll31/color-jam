# color-jam
A javascript page to look at colors

I made this in an afternoon, so it sucks but it gets the job done - which is to look at colors next to each other.

New color box take CSS compatible colors, HTML, rgb, and hex. Same with background color.

Add predefined colors using /js/colorlist.js with format:

var COLOR_OBJ = {
    color_name {
        id: "ABC-123",
	color: "#DEADBE"
    },
    another_color {
        id: "ABC-124",
	color: "rgb(53, 169, 127)"
    },
    one_more {
        id: "ABC-125",
	color: "red"
    }
};
