# stdin_bin_to_stdout_hex
Simple tool converts binary to hex text

It reads stdin and writes to stdout.

    gcc stdin_bin_to_stdout_hex.c -o stdin_bin_to_stdout_hex
    echo 'Hello, World!' | ./stdin_bin_to_stdout_hex
    cat some_file.bin | ./stdin_bin_to_stdout_hex
