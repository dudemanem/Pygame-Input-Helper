# Pygame-Input-Helper

 -Streamlines input handling in Pygame. 
 -Can detect keypresses and held down keys.
 -Changes pygame keycodes to make them simpler and easier to remember.

 *GUIDE*
 
     1. Before using, you have to import it.
       - import input_helper.py
     
     2. Create instance of the eInput class.
       - input_helper = eInput()

     3. Then before detecting input, get all keypress events and save them to a variable. If keys are detected in a loop this must be done before each iteration.
       - key_events = input_helper.get_key_events()

     4. To check keypresses, use is_key_down(self, keycheck, events).
       - if input_helper.is_key_down(input_helper.keys.space, key_events):
           print("space pressed")

     5. To check if a key is held down, use is_key_held(self,check).
       - if input_helper.is_key_held(input_helper.keys.space):
           print("space is being held down")

     6. To check for mouse button clicks use... will finish this later :3



*Complete List of Current Keycodes and Their Translation in the Keys Subclass*

        backspace = pygame.K_BACKSPACE
        tab = pygame.K_TAB
        clear = pygame.K_CLEAR
        enter = pygame.K_RETURN
        pause = pygame.K_PAUSE
        escape = pygame.K_ESCAPE
        space = pygame.K_SPACE
        exclaim = pygame.K_EXCLAIM
        doublequote = pygame.K_QUOTEDBL
        pound = pygame.K_HASH
        dollar = pygame.K_DOLLAR
        ampersand = pygame.K_AMPERSAND
        quote = pygame.K_QUOTE
        leftparen = pygame.K_LEFTPAREN
        rightparen = pygame.K_RIGHTPAREN
        asterisk = pygame.K_ASTERISK
        plus = pygame.K_PLUS
        comma = pygame.K_COMMA
        minus = pygame.K_MINUS
        period = pygame.K_PERIOD
        slash = pygame.K_SLASH
        n0 = pygame.K_0
        n1 = pygame.K_1
        n2 = pygame.K_2
        n3 = pygame.K_3
        n4 = pygame.K_4
        n5 = pygame.K_5
        n6 = pygame.K_6
        n7 = pygame.K_7
        n8 = pygame.K_8
        n9 = pygame.K_9
        colon = pygame.K_COLON
        semicolon = pygame.K_SEMICOLON
        lessthan = pygame.K_LESS
        equals = pygame.K_EQUALS
        greaterthan = pygame.K_GREATER
        question = pygame.K_QUESTION
        at = pygame.K_AT
        leftbracket = pygame.K_LEFTBRACKET
        backslash = pygame.K_BACKSLASH
        rightbracket = pygame.K_RIGHTBRACKET
        caret = pygame.K_CARET
        underscore = pygame.K_UNDERSCORE
        grave = pygame.K_BACKQUOTE
        a = pygame.K_a
        b = pygame.K_b
        c = pygame.K_c
        d = pygame.K_d
        e = pygame.K_e
        f = pygame.K_f
        g = pygame.K_g
        h = pygame.K_h
        i = pygame.K_i
        j = pygame.K_j
        k = pygame.K_k
        l = pygame.K_l
        m = pygame.K_m
        n = pygame.K_n
        o = pygame.K_o
        p = pygame.K_p
        q = pygame.K_q
        r = pygame.K_r
        s = pygame.K_s
        t = pygame.K_t
        u = pygame.K_u
        v = pygame.K_v
        w = pygame.K_w
        x = pygame.K_x
        y = pygame.K_y
        z = pygame.K_z
        delete = pygame.K_DELETE
        p0 = pygame.K_KP0
        p1 = pygame.K_KP1
        p2 = pygame.K_KP2
        p3 = pygame.K_KP3
        p4 = pygame.K_KP4
        p5 = pygame.K_KP5
        p6 = pygame.K_KP6
        p7 = pygame.K_KP7
        p8 = pygame.K_KP8
        p9 = pygame.K_KP9
        kp_period = pygame.K_KP_PERIOD
        kp_divide = pygame.K_KP_DIVIDE
        kp_multiply = pygame.K_KP_MULTIPLY
        kp_minus = pygame.K_KP_MINUS
        kp_plus = pygame.K_KP_PLUS
        kp_enter = pygame.K_KP_ENTER
        kp_equals = pygame.K_KP_EQUALS
        up = pygame.K_UP
        down = pygame.K_DOWN
        left = pygame.K_LEFT
        right = pygame.K_RIGHT
        insert = pygame.K_INSERT
        home = pygame.K_HOME
        end = pygame.K_END
        pageup = pygame.K_PAGEUP
        pagedown = pygame.K_PAGEDOWN
        f1 = pygame.K_F1
        f2 = pygame.K_F2
        f3 = pygame.K_F3
        f4 = pygame.K_F4
        f5 = pygame.K_F5
        f6 = pygame.K_F6
        f7 = pygame.K_F7
        f8 = pygame.K_F8
        f9 = pygame.K_F9
        f10 = pygame.K_F10
        f11 = pygame.K_F11
        f12 = pygame.K_F12
        f13 = pygame.K_F13
        f14 = pygame.K_F14
        f15 = pygame.K_F15
        numlock = pygame.K_NUMLOCK
        capslock = pygame.K_CAPSLOCK
        scrollock = pygame.K_SCROLLOCK
        rshift = pygame.K_RSHIFT
        lshift = pygame.K_LSHIFT
        rctrl = pygame.K_RCTRL
        lctrl = pygame.K_LCTRL
        ralt = pygame.K_RALT
        lalt = pygame.K_LALT
        rmeta = pygame.K_RMETA
        lmeta = pygame.K_LMETA
        lsuper = pygame.K_LSUPER
        rsuper = pygame.K_RSUPER
        mode = pygame.K_MODE
        help_key = pygame.K_HELP
        print_key = pygame.K_PRINT
        sysreq = pygame.K_SYSREQ
        break_key = pygame.K_BREAK
        menu = pygame.K_MENU
        power = pygame.K_POWER
        euro = pygame.K_EURO
        ac_back = pygame.K_AC_BACK
