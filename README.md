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

# Server Metrics 2026-03-22 06:30:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 33873.2 (9h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649620
telemt_connections_bad_total 40275
telemt_connections_current 1369
telemt_connections_me_current 1369
telemt_handshake_timeouts_total 31992
telemt_upstream_connect_attempt_total 13869
telemt_upstream_connect_success_total 13868
telemt_upstream_connect_attempts_per_request{bucket="1"} 13868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 368
telemt_me_reconnect_success_total 217
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 234659
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537958
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 4531
telemt_desync_full_logged_total 1257
telemt_desync_suppressed_total 3274
telemt_desync_frames_bucket_total{bucket="1_2"} 1495
telemt_desync_frames_bucket_total{bucket="3_10"} 1696
telemt_desync_frames_bucket_total{bucket="gt_10"} 1340
telemt_pool_swap_total 37
telemt_pool_force_close_total 988
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 12551
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 978
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11563
telemt_me_writer_teardown_success_total{mode="normal"} 12748
telemt_me_writer_teardown_noop_total 12552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25300
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.416585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25300
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 536860
telemt_user_connections_current{user="hello"} 1369
telemt_user_octets_from_client{user="hello"} 7428601328 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 187211975368 (174.35 GB)
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47239.1 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1110714
telemt_connections_bad_total 102639
telemt_connections_current 1030
telemt_connections_me_current 1030
telemt_handshake_timeouts_total 36350
telemt_upstream_connect_attempt_total 25046
telemt_upstream_connect_success_total 24686
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 25001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1882
telemt_me_reconnect_success_total 721
telemt_me_reader_eof_total 637
telemt_me_idle_close_by_peer_total 637
telemt_me_route_drop_no_conn_total 411711
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846729
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 381
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 3558
telemt_desync_full_logged_total 2077
telemt_desync_suppressed_total 1481
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1432
telemt_pool_swap_total 50
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 19608
telemt_me_writer_removed_unexpected_total 611
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1701
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18502
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18255
telemt_me_writer_teardown_success_total{mode="normal"} 20203
telemt_me_writer_teardown_noop_total 19608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39811
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.072032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39811
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 550
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 848365
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 13824002723 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 316044772654 (294.34 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 122099.1 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8635377
telemt_connections_bad_total 780268
telemt_connections_current 3788
telemt_connections_me_current 3788
telemt_handshake_timeouts_total 276021
telemt_upstream_connect_attempt_total 45279
telemt_upstream_connect_success_total 45201
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1732
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 903
telemt_me_route_drop_no_conn_total 4753142
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6863084
telemt_me_endpoint_quarantine_total 777
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 919
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
telemt_me_writers_active_current 47
telemt_desync_total 29290
telemt_desync_full_logged_total 9725
telemt_desync_suppressed_total 19565
telemt_desync_frames_bucket_total{bucket="1_2"} 6342
telemt_desync_frames_bucket_total{bucket="3_10"} 11431
telemt_desync_frames_bucket_total{bucket="gt_10"} 11517
telemt_pool_swap_total 132
telemt_pool_force_close_total 4360
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 41337
telemt_me_writer_removed_unexpected_total 868
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38280
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 257
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36977
telemt_me_writer_teardown_success_total{mode="normal"} 41712
telemt_me_writer_teardown_noop_total 41381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.754968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6854167
telemt_user_connections_current{user="hello"} 3788
telemt_user_octets_from_client{user="hello"} 116050752136 (108.08 GB)
telemt_user_octets_to_client{user="hello"} 2338812484608 (2.13 TB)
telemt_user_unique_ips_current{user="hello"} 1551
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 122100.3 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7123271
telemt_connections_bad_total 630837
telemt_connections_current 3529
telemt_connections_me_current 3529
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 236890
telemt_upstream_connect_attempt_total 49221
telemt_upstream_connect_success_total 48816
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 49024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2067
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 2411268
telemt_me_route_drop_channel_closed_total 294
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5289748
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 941
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 24476
telemt_desync_full_logged_total 8411
telemt_desync_suppressed_total 16065
telemt_desync_frames_bucket_total{bucket="1_2"} 5854
telemt_desync_frames_bucket_total{bucket="3_10"} 9501
telemt_desync_frames_bucket_total{bucket="gt_10"} 9121
telemt_pool_swap_total 133
telemt_pool_force_close_total 3961
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 402
telemt_me_draining_writers_reap_progress_total 39766
telemt_me_writer_removed_unexpected_total 900
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35805
telemt_me_writer_teardown_success_total{mode="normal"} 40595
telemt_me_writer_teardown_noop_total 39772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.059318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 402
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 824
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5211013
telemt_user_connections_current{user="hello"} 3529
telemt_user_octets_from_client{user="hello"} 149787265557 (139.50 GB)
telemt_user_octets_to_client{user="hello"} 2515849335607 (2.29 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1415
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 122064.5 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6903884
telemt_connections_bad_total 576999
telemt_connections_current 2920
telemt_connections_me_current 2920
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232280
telemt_upstream_connect_attempt_total 55721
telemt_upstream_connect_success_total 55120
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2587
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 2491212
telemt_me_route_drop_channel_closed_total 156
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5131908
telemt_me_endpoint_quarantine_total 871
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 906
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 47
telemt_desync_total 24356
telemt_desync_full_logged_total 8253
telemt_desync_suppressed_total 16103
telemt_desync_frames_bucket_total{bucket="1_2"} 5908
telemt_desync_frames_bucket_total{bucket="3_10"} 9345
telemt_desync_frames_bucket_total{bucket="gt_10"} 9103
telemt_pool_swap_total 131
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40737
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 250
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36905
telemt_me_writer_teardown_success_total{mode="normal"} 41781
telemt_me_writer_teardown_noop_total 40749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.067245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5126061
telemt_user_connections_current{user="hello"} 2920
telemt_user_octets_from_client{user="hello"} 139817653043 (130.22 GB)
telemt_user_octets_to_client{user="hello"} 2332684495383 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1274
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 122103.7 (33h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22072796
telemt_connections_bad_total 1871018
telemt_connections_current 4910
telemt_connections_me_current 4910
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 664522
telemt_upstream_connect_attempt_total 225363
telemt_upstream_connect_success_total 206201
telemt_upstream_connect_fail_total 17228
telemt_upstream_connect_attempts_per_request{bucket="1"} 223429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17228
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66346
telemt_me_reconnect_success_total 2598
telemt_me_reader_eof_total 1634
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 41773344
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17744707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 958
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 34271
telemt_desync_full_logged_total 10303
telemt_desync_suppressed_total 23968
telemt_desync_frames_bucket_total{bucket="1_2"} 7566
telemt_desync_frames_bucket_total{bucket="3_10"} 15151
telemt_desync_frames_bucket_total{bucket="gt_10"} 11554
telemt_pool_swap_total 126
telemt_pool_force_close_total 4019
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 909
telemt_me_draining_writers_reap_progress_total 38266
telemt_me_writer_removed_unexpected_total 2409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35231
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34247
telemt_me_writer_teardown_success_total{mode="normal"} 40425
telemt_me_writer_teardown_noop_total 38296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.686232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 909
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1767
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17897327
telemt_user_connections_current{user="hello"} 4910
telemt_user_octets_from_client{user="hello"} 265954482845 (247.69 GB)
telemt_user_octets_to_client{user="hello"} 1369720910723 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1825
telemt_user_unique_ips_recent_window{user="hello"} 931
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 122071.3 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6631491
telemt_connections_bad_total 619264
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 138019
telemt_upstream_connect_attempt_total 64327
telemt_upstream_connect_success_total 63588
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 64221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69990
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1685
telemt_me_idle_close_by_peer_total 1684
telemt_me_route_drop_no_conn_total 2540918
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5177744
telemt_me_endpoint_quarantine_total 822
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 928
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25791
telemt_desync_full_logged_total 9011
telemt_desync_suppressed_total 16780
telemt_desync_frames_bucket_total{bucket="1_2"} 5093
telemt_desync_frames_bucket_total{bucket="3_10"} 9925
telemt_desync_frames_bucket_total{bucket="gt_10"} 10773
telemt_pool_swap_total 127
telemt_pool_force_close_total 3642
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 42954
telemt_me_writer_removed_unexpected_total 1718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39312
telemt_me_writer_teardown_success_total{mode="normal"} 44707
telemt_me_writer_teardown_noop_total 42955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87662
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.900862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87662
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1594
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5169455
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 132454536024 (123.36 GB)
telemt_user_octets_to_client{user="hello"} 2160771847654 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1449
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 58907.1 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4745907
telemt_connections_bad_total 198103
telemt_connections_current 2960
telemt_connections_me_current 2960
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1864697
telemt_upstream_connect_attempt_total 33129
telemt_upstream_connect_success_total 32905
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 33122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 46177
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 746
telemt_me_route_drop_no_conn_total 1175675
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2365526
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 455
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12650
telemt_desync_full_logged_total 4369
telemt_desync_suppressed_total 8281
telemt_desync_frames_bucket_total{bucket="1_2"} 2444
telemt_desync_frames_bucket_total{bucket="3_10"} 4846
telemt_desync_frames_bucket_total{bucket="gt_10"} 5360
telemt_pool_swap_total 64
telemt_pool_force_close_total 1877
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 164
telemt_me_draining_writers_reap_progress_total 21622
telemt_me_writer_removed_unexpected_total 816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20635
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19745
telemt_me_writer_teardown_success_total{mode="normal"} 22468
telemt_me_writer_teardown_noop_total 21624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44092
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.766285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44092
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 164
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 940
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2367569
telemt_user_connections_current{user="hello"} 2960
telemt_user_octets_from_client{user="hello"} 61799068480 (57.55 GB)
telemt_user_octets_to_client{user="hello"} 1050268562626 (978.14 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 477
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39878.3 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294738
telemt_connections_bad_total 2055
telemt_connections_current 599
telemt_connections_me_current 599
telemt_handshake_timeouts_total 7088
telemt_upstream_connect_attempt_total 19220
telemt_upstream_connect_success_total 19172
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 19216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 826
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 85738
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265311
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 348
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 47
telemt_desync_total 1307
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 500
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 44
telemt_pool_force_close_total 986
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17388
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16541
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16402
telemt_me_writer_teardown_success_total{mode="normal"} 17662
telemt_me_writer_teardown_noop_total 17388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.363360
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 264900
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 4384811380 (4.08 GB)
telemt_user_octets_to_client{user="hello"} 155289518204 (144.62 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 122075.6 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8046181
telemt_connections_bad_total 814654
telemt_connections_current 3739
telemt_connections_me_current 3739
telemt_handshake_timeouts_total 226875
telemt_upstream_connect_attempt_total 48005
telemt_upstream_connect_success_total 47830
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1762
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 2275743
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6008736
telemt_me_endpoint_quarantine_total 872
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 936
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 23640
telemt_desync_full_logged_total 7778
telemt_desync_suppressed_total 15862
telemt_desync_frames_bucket_total{bucket="1_2"} 5902
telemt_desync_frames_bucket_total{bucket="3_10"} 8622
telemt_desync_frames_bucket_total{bucket="gt_10"} 9116
telemt_pool_swap_total 135
telemt_pool_force_close_total 3602
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 424
telemt_me_draining_writers_reap_progress_total 43355
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3392
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40881
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39753
telemt_me_writer_teardown_success_total{mode="normal"} 44273
telemt_me_writer_teardown_noop_total 43357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.218060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 424
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5982906
telemt_user_connections_current{user="hello"} 3739
telemt_user_octets_from_client{user="hello"} 117238661552 (109.19 GB)
telemt_user_octets_to_client{user="hello"} 2807692592612 (2.55 TB)
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 122072.2 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7029333
telemt_connections_bad_total 708918
telemt_connections_current 3750
telemt_connections_me_current 3750
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 188297
telemt_upstream_connect_attempt_total 63792
telemt_upstream_connect_success_total 63304
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 63729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25750
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 5864
telemt_me_reconnect_success_total 1312
telemt_me_reader_eof_total 1179
telemt_me_idle_close_by_peer_total 1179
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2334328
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5372965
telemt_me_endpoint_quarantine_total 964
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 936
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 46
telemt_desync_total 22600
telemt_desync_full_logged_total 7507
telemt_desync_suppressed_total 15093
telemt_desync_frames_bucket_total{bucket="1_2"} 5655
telemt_desync_frames_bucket_total{bucket="3_10"} 8262
telemt_desync_frames_bucket_total{bucket="gt_10"} 8683
telemt_pool_swap_total 133
telemt_pool_force_close_total 3547
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 41829
telemt_me_writer_removed_unexpected_total 1191
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38282
telemt_me_writer_teardown_success_total{mode="normal"} 43081
telemt_me_writer_teardown_noop_total 41833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.070431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1021
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5375200
telemt_user_connections_current{user="hello"} 3750
telemt_user_octets_from_client{user="hello"} 100276838349 (93.39 GB)
telemt_user_octets_to_client{user="hello"} 2334955409512 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1481
telemt_user_unique_ips_recent_window{user="hello"} 506
```