# cdi-04
Luis Britez
4°1AV
comision A

#include <stdio.h>
#include "pico/stdlib.h"

int main() {
  stdio_init_all();
gpio_init (25);
gpio_set_dir (25, true);

while (true){


gpio_put (25, true);
sleep_ms(250);
gpio_put (25, false);
sleep_ms(250);
}
}
