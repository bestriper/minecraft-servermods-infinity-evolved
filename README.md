Infinity Server Minecraft - Docker Server
==============================

Dockerfile for Minecraft Mods Server Infinity evolved

To simply use the latest stable version, run:

Run with:

```bash
docker run -d \
	-p 25565:25565 \
	-v /local/path/to/world:/minecraft/world \
	bestriper/minecraft-servermods-infinity-evolved
```
where the default server port, 25565, will be exposed on your host machine. If you want to serve up multiple Minecraft servers or just use an alternate port, change the host-side port mapping such as:

```bash
docker run -p 25566:25565 ...
```
will service port 25566

If you want the docker to create your own map, do not put any route or you can indicate where you want the volume of the map and he will generate it only when you start it.

==============================
:-:-: BeStRiPeR :-:-: