jobs:
  devcard:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - name: devcard
        uses: dailydotdev/action-devcard@2.1.0
        with:
          devcard_id: ${{ secrets.DEVCARD_ID }}
