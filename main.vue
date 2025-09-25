<script setup lang="ts">
const longerName = {
    alsoQuiteALongName: "value",
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
                                                <div
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
