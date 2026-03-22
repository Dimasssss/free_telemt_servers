# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 12:13:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 54398.8 (15h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1616675
telemt_connections_bad_total 76128
telemt_connections_current 1736
telemt_connections_me_current 1736
telemt_handshake_timeouts_total 72215
telemt_upstream_connect_attempt_total 20738
telemt_upstream_connect_success_total 20737
telemt_upstream_connect_attempts_per_request{bucket="1"} 20737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 773
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 1093113
telemt_me_route_drop_channel_closed_total 485
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368226
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 435
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 8143
telemt_desync_full_logged_total 2447
telemt_desync_suppressed_total 5696
telemt_desync_frames_bucket_total{bucket="1_2"} 2312
telemt_desync_frames_bucket_total{bucket="3_10"} 3070
telemt_desync_frames_bucket_total{bucket="gt_10"} 2761
telemt_pool_swap_total 60
telemt_pool_force_close_total 1794
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 277
telemt_me_draining_writers_reap_progress_total 18923
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17791
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17129
telemt_me_writer_teardown_success_total{mode="normal"} 19127
telemt_me_writer_teardown_noop_total 18925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 135.194996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 277
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1365528
telemt_user_connections_current{user="hello"} 1736
telemt_user_octets_from_client{user="hello"} 21389003460 (19.92 GB)
telemt_user_octets_to_client{user="hello"} 405067263116 (377.25 GB)
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 67765.1 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2616182
telemt_connections_bad_total 233730
telemt_connections_current 2166
telemt_connections_me_current 2166
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 60231
telemt_upstream_connect_attempt_total 44800
telemt_upstream_connect_success_total 44276
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 44740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3450
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1441
telemt_me_idle_close_by_peer_total 1441
telemt_me_route_drop_no_conn_total 2303051
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2055181
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 531
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 86
telemt_desync_total 8106
telemt_desync_full_logged_total 4576
telemt_desync_suppressed_total 3530
telemt_desync_frames_bucket_total{bucket="1_2"} 1882
telemt_desync_frames_bucket_total{bucket="3_10"} 3155
telemt_desync_frames_bucket_total{bucket="gt_10"} 3069
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 26924
telemt_me_writer_removed_unexpected_total 1403
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2989
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25336
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25034
telemt_me_writer_teardown_success_total{mode="normal"} 28325
telemt_me_writer_teardown_noop_total 26924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.307784
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2066978
telemt_user_connections_current{user="hello"} 2166
telemt_user_octets_from_client{user="hello"} 25646615055 (23.89 GB)
telemt_user_octets_to_client{user="hello"} 503914415382 (469.31 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 142625.0 (39h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12719120
telemt_connections_bad_total 1109409
telemt_connections_current 5015
telemt_connections_me_current 5015
telemt_handshake_timeouts_total 330689
telemt_upstream_connect_attempt_total 52021
telemt_upstream_connect_success_total 51941
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2281
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1165
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 10394694
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10164214
telemt_me_endpoint_quarantine_total 902
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1061
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41745
telemt_desync_full_logged_total 13351
telemt_desync_suppressed_total 28394
telemt_desync_frames_bucket_total{bucket="1_2"} 9404
telemt_desync_frames_bucket_total{bucket="3_10"} 16293
telemt_desync_frames_bucket_total{bucket="gt_10"} 16048
telemt_pool_swap_total 153
telemt_pool_force_close_total 5222
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 823
telemt_me_draining_writers_reap_progress_total 47460
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42238
telemt_me_writer_teardown_success_total{mode="normal"} 47952
telemt_me_writer_teardown_noop_total 47508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95460
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.554123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95460
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 823
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1043
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 10152695
telemt_user_connections_current{user="hello"} 5015
telemt_user_octets_from_client{user="hello"} 150429402356 (140.10 GB)
telemt_user_octets_to_client{user="hello"} 2835201038796 (2.58 TB)
telemt_user_unique_ips_current{user="hello"} 1880
telemt_user_unique_ips_recent_window{user="hello"} 742
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 142626.3 (39h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9609583
telemt_connections_bad_total 871186
telemt_connections_current 5011
telemt_connections_me_current 5011
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 289223
telemt_upstream_connect_attempt_total 78351
telemt_upstream_connect_success_total 77226
telemt_upstream_connect_fail_total 811
telemt_upstream_connect_attempts_per_request{bucket="1"} 78037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3669
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 811
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3325
telemt_me_reconnect_success_total 1351
telemt_me_reader_eof_total 1235
telemt_me_idle_close_by_peer_total 1235
telemt_me_route_drop_no_conn_total 3857692
telemt_me_route_drop_channel_closed_total 397
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7166840
telemt_me_endpoint_quarantine_total 900
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1089
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 32291
telemt_desync_full_logged_total 10948
telemt_desync_suppressed_total 21343
telemt_desync_frames_bucket_total{bucket="1_2"} 7942
telemt_desync_frames_bucket_total{bucket="3_10"} 12443
telemt_desync_frames_bucket_total{bucket="gt_10"} 11906
telemt_pool_swap_total 153
telemt_pool_force_close_total 4672
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 568
telemt_me_draining_writers_reap_progress_total 45720
telemt_me_writer_removed_unexpected_total 1267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4073
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41048
telemt_me_writer_teardown_success_total{mode="normal"} 46854
telemt_me_writer_teardown_noop_total 45728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92582
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 82.671677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92582
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 568
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1152
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7107437
telemt_user_connections_current{user="hello"} 5011
telemt_user_octets_from_client{user="hello"} 183708074217 (171.09 GB)
telemt_user_octets_to_client{user="hello"} 3233394546878 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1867
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 142591.5 (39h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9075618
telemt_connections_bad_total 761093
telemt_connections_current 4301
telemt_connections_me_current 4301
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 286171
telemt_upstream_connect_attempt_total 62717
telemt_upstream_connect_success_total 61982
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 62129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1419
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3824
telemt_me_reconnect_success_total 1625
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 3952402
telemt_me_route_drop_channel_closed_total 274
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6839023
telemt_me_endpoint_quarantine_total 980
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 1044
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 52
telemt_desync_total 32080
telemt_desync_full_logged_total 10723
telemt_desync_suppressed_total 21357
telemt_desync_frames_bucket_total{bucket="1_2"} 8063
telemt_desync_frames_bucket_total{bucket="3_10"} 12318
telemt_desync_frames_bucket_total{bucket="gt_10"} 11699
telemt_pool_swap_total 149
telemt_pool_force_close_total 4633
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 561
telemt_me_draining_writers_reap_progress_total 46508
telemt_me_writer_removed_unexpected_total 1526
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4475
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43481
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 479
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41875
telemt_me_writer_teardown_success_total{mode="normal"} 47956
telemt_me_writer_teardown_noop_total 46528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94484
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.116206
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94484
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 561
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 52
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 6829776
telemt_user_connections_current{user="hello"} 4301
telemt_user_octets_from_client{user="hello"} 165533879595 (154.17 GB)
telemt_user_octets_to_client{user="hello"} 2926616441671 (2.66 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1644
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 12885.6 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5457998
telemt_connections_bad_total 327667
telemt_connections_current 6639
telemt_connections_me_current 6639
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 85414
telemt_upstream_connect_attempt_total 23859
telemt_upstream_connect_success_total 22794
telemt_upstream_connect_fail_total 836
telemt_upstream_connect_attempts_per_request{bucket="1"} 23630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4625
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 836
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 2295
telemt_me_reconnect_success_total 357
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 12698986
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4573348
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 6907
telemt_desync_full_logged_total 1769
telemt_desync_suppressed_total 5138
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 2762
telemt_desync_frames_bucket_total{bucket="gt_10"} 2889
telemt_pool_swap_total 12
telemt_pool_force_close_total 505
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 3378
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 596
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3055
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2873
telemt_me_writer_teardown_success_total{mode="normal"} 3651
telemt_me_writer_teardown_noop_total 3381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.720193
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4586888
telemt_user_connections_current{user="hello"} 6639
telemt_user_octets_from_client{user="hello"} 25028806970 (23.31 GB)
telemt_user_octets_to_client{user="hello"} 134037180851 (124.83 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2351
telemt_user_unique_ips_recent_window{user="hello"} 1275
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 142597.3 (39h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8809408
telemt_connections_bad_total 749861
telemt_connections_current 5243
telemt_connections_me_current 5243
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 186705
telemt_upstream_connect_attempt_total 88051
telemt_upstream_connect_success_total 87181
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 87929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71018
telemt_me_reconnect_success_total 2325
telemt_me_reader_eof_total 2064
telemt_me_idle_close_by_peer_total 2063
telemt_me_route_drop_no_conn_total 4076266
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6958421
telemt_me_endpoint_quarantine_total 947
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1069
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 35556
telemt_desync_full_logged_total 12253
telemt_desync_suppressed_total 23303
telemt_desync_frames_bucket_total{bucket="1_2"} 7264
telemt_desync_frames_bucket_total{bucket="3_10"} 13659
telemt_desync_frames_bucket_total{bucket="gt_10"} 14633
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 48847
telemt_me_writer_removed_unexpected_total 2093
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44594
telemt_me_writer_teardown_success_total{mode="normal"} 50965
telemt_me_writer_teardown_noop_total 48848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.852778
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 4241
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 6961236
telemt_user_connections_current{user="hello"} 5243
telemt_user_octets_from_client{user="hello"} 165083595191 (153.75 GB)
telemt_user_octets_to_client{user="hello"} 2701344958505 (2.46 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2148
telemt_user_unique_ips_recent_window{user="hello"} 670
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 79433.3 (22h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8274397
telemt_connections_bad_total 293752
telemt_connections_current 4151
telemt_connections_me_current 4151
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3456247
telemt_upstream_connect_attempt_total 40278
telemt_upstream_connect_success_total 39987
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47840
telemt_me_reconnect_success_total 1394
telemt_me_reader_eof_total 1062
telemt_me_idle_close_by_peer_total 1062
telemt_me_route_drop_no_conn_total 2797677
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4033629
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 603
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 88
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22267
telemt_desync_full_logged_total 7437
telemt_desync_suppressed_total 14830
telemt_desync_frames_bucket_total{bucket="1_2"} 4564
telemt_desync_frames_bucket_total{bucket="3_10"} 8645
telemt_desync_frames_bucket_total{bucket="gt_10"} 9058
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 27802
telemt_me_writer_removed_unexpected_total 1129
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2515
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26442
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25252
telemt_me_writer_teardown_success_total{mode="normal"} 28957
telemt_me_writer_teardown_noop_total 27809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56766
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.734581
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56766
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4030672
telemt_user_connections_current{user="hello"} 4151
telemt_user_octets_from_client{user="hello"} 91366801620 (85.09 GB)
telemt_user_octets_to_client{user="hello"} 1592877646650 (1.45 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1648
telemt_user_unique_ips_recent_window{user="hello"} 650
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60404.0 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666222
telemt_connections_bad_total 7277
telemt_connections_current 968
telemt_connections_me_current 968
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12882
telemt_upstream_connect_attempt_total 31196
telemt_upstream_connect_success_total 31118
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 31184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 578
telemt_me_idle_close_by_peer_total 578
telemt_me_route_drop_no_conn_total 222616
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 601271
telemt_me_endpoint_quarantine_total 555
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 3297
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 2335
telemt_desync_frames_bucket_total{bucket="1_2"} 832
telemt_desync_frames_bucket_total{bucket="3_10"} 1301
telemt_desync_frames_bucket_total{bucket="gt_10"} 1164
telemt_pool_swap_total 64
telemt_pool_force_close_total 1544
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 25464
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1923
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24120
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23920
telemt_me_writer_teardown_success_total{mode="normal"} 26043
telemt_me_writer_teardown_noop_total 25466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51509
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.766764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51509
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 603080
telemt_user_connections_current{user="hello"} 968
telemt_user_octets_from_client{user="hello"} 11468069929 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 285076134667 (265.50 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 142601.5 (39h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10709831
telemt_connections_bad_total 1246995
telemt_connections_current 5385
telemt_connections_me_current 5385
telemt_handshake_timeouts_total 286910
telemt_upstream_connect_attempt_total 54303
telemt_upstream_connect_success_total 54092
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 54255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 2117
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 3227168
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8022824
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1073
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 32751
telemt_desync_full_logged_total 10772
telemt_desync_suppressed_total 21979
telemt_desync_frames_bucket_total{bucket="1_2"} 7916
telemt_desync_frames_bucket_total{bucket="3_10"} 12067
telemt_desync_frames_bucket_total{bucket="gt_10"} 12768
telemt_pool_swap_total 158
telemt_pool_force_close_total 4317
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 541
telemt_me_draining_writers_reap_progress_total 48951
telemt_me_writer_removed_unexpected_total 1048
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46043
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4175
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 142
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44634
telemt_me_writer_teardown_success_total{mode="normal"} 50034
telemt_me_writer_teardown_noop_total 48953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98987
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.397401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98987
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 541
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7994017
telemt_user_connections_current{user="hello"} 5385
telemt_user_octets_from_client{user="hello"} 154095304032 (143.51 GB)
telemt_user_octets_to_client{user="hello"} 3661333373940 (3.33 TB)
telemt_user_unique_ips_current{user="hello"} 1791
telemt_user_unique_ips_recent_window{user="hello"} 786
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 142598.6 (39h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9359372
telemt_connections_bad_total 1055423
telemt_connections_current 5807
telemt_connections_me_current 5807
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 241890
telemt_upstream_connect_attempt_total 79141
telemt_upstream_connect_success_total 78565
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 79066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1979
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_reconnect_attempts_total 6952
telemt_me_reconnect_success_total 1722
telemt_me_reader_eof_total 1548
telemt_me_idle_close_by_peer_total 1548
telemt_me_seq_mismatch_total 69
telemt_me_route_drop_no_conn_total 3843885
telemt_me_route_drop_channel_closed_total 291
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7185897
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1080
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 32042
telemt_desync_full_logged_total 10468
telemt_desync_suppressed_total 21574
telemt_desync_frames_bucket_total{bucket="1_2"} 7935
telemt_desync_frames_bucket_total{bucket="3_10"} 11907
telemt_desync_frames_bucket_total{bucket="gt_10"} 12200
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 524
telemt_me_draining_writers_reap_progress_total 47720
telemt_me_writer_removed_unexpected_total 1570
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44599
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43541
telemt_me_writer_teardown_success_total{mode="normal"} 49355
telemt_me_writer_teardown_noop_total 47724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.181055
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 524
telemt_me_refill_failed_total 296
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 93
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 7193796
telemt_user_connections_current{user="hello"} 5807
telemt_user_octets_from_client{user="hello"} 127722520649 (118.95 GB)
telemt_user_octets_to_client{user="hello"} 2901522836843 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2306
telemt_user_unique_ips_recent_window{user="hello"} 641
```