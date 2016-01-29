
Font Module
u32 Font.load(string filename) - Load a TTF font.

Sample usage: my_font = Font.load("/font.ttf")
void Font.setPixelSizes(u32 font,u32 size) - Set size for a font.

Sample usage: Font.setPixelSizes(my_font,18)
void Font.print(u32 font, int x, int y, string text, u32 color, u32 screen, [u32 side]) - Print a text with a font.

Sample usage: Font.print(my_font, 5, 5, "Hello World!", Color.new(255,255,255), TOP_SCREEN)
void Font.unload(u32 font) - Free a font.

Sample usage: Font.unload(my_font)

