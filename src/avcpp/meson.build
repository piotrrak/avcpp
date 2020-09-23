foreach hdr : avcpp_header
    configure_file(
        copy: true,
        input: hdr,
        output: '@PLAINNAME@'
    )
endforeach

subdir('filters')
