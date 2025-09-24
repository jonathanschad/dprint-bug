<script setup lang="ts">
import copyButton from '@/components/buttons/copy-button.vue';

const longerName = {
    alsoQuiteALongName: 'value',
};
</script>

<template>
  <div>
    <div>
      <div>
        <div>
          <div>
            <div>
              <div>
                <div>
                  <div>
                    <div>
                      <td>
                        <code class="value-uuid">{{
                          longerName.alsoQuiteALongName
                        }}</code>
                        <copy-button
                          v-if="longerName.alsoQuiteALongName"
                          :value="longerName.alsoQuiteALongName"
                        />
                      </td>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
