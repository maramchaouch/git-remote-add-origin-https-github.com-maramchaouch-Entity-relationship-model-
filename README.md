                              +-------------------------+
                              |      Gymnasium          |
                              +-------------------------+
                              | Name                    |
                              | Address                 |
                              | Telephone number        |
                              +-------------------------+
                                        | 1
                                        |
                                        |
                                        |
                             +----------+-----------+
                             |                      |
             attends (M:N)   |                      |   holds (1:M)
                             |       Session        |
                             |                      |
                             | Type of sport        |
                             | Schedule             |
                             | Maximum capacity     |
                             +----------+-----------+
                                        | 1
                                        |
                                        |
                                        |
                             +----------+-----------+
                             |                      |
            leads (M:1)      |                      |    registers (1:M)
                             |       Coach          |
                             |                      |
                             | Last name            |
                             | First name           |
                             | Age                  |
                             | Specialty            |
                             +----------------------+
