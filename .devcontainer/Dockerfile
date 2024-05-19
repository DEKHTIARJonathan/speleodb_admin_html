# We'll base our dev container image on Alpine Linux.
FROM nginx:latest

# Finally, we'll remove nginx's default content and replace it
# with a symlink to our source code.

RUN rm -rf /usr/share/nginx/html
RUN ln -s /workspaces/speleodb_html /usr/share/nginx/html