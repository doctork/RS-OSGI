RSPS using OSGi
==========
Those of you who are not familiar with OSGi visit <a href="http://www.osgi.org/">OSGi.org</a>.

Core
----------
The core will be split into several sections, scripting implementations (<a href="http://www.jruby.org/">JRuby</a>, <a href="http://www.jython.org/">Jython</a>), general networking (e.g. Implementation of <a href="http://www.jboss.org/netty/">JBoss Netty</a> and perhaps also raw NIO, being that the aim of the base is power and portability), then finally various systems like EventManager, TaskManager etc.

Inspiration
----------
The whole idea of this base was built around that of <a href="https://github.com/parabolika">Parabolika</a> and his <a href="https://github.com/parabolika/osgi-serv">osgi-serv</a>