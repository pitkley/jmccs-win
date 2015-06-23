# jMCCS - Win implementation

This Maven project implements the `Monitor`-interface and extends the `MonitorManager`-class that are required by
[jMCCS][jmccs]. It uses [JNA][jna] to interact with the native Windows-API, specifically with the libraries `User32` and `Dxva2`.

## Usage

As this is a Maven project, you can include this project in your application simply by depending on it.
(**Note:** the package is not yet in the Maven central repository. The following snippet will not work until it is pushed.)

```xml
<dependency>
    <groupId>de.pitkley</groupId>
    <artifactId>jmccs-win</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

## License

This project is licensed under MIT.

[jmccs]: https://github.com/pitkley/jmccs
[jna]: https://github.com/twall/jna
