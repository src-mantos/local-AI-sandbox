FROM pytorch/pytorch:latest

# Set the working directory
WORKDIR /workspaces

# Copy project files into the container
COPY ../ .

# COPY --from=0 local-AI-sandbox /workspaces/local-AI-sandbox

RUN apt-get update && apt-get install -y git

# RUN mkdir -p /workspaces/local-AI-sandbox
# WORKDIR /workspaces/local-AI-sandbox
RUN git clone https://github.com/Stability-AI/generative-models.git


# Set the default command to run when the container starts
CMD ["bash"]
