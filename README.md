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

# Server Metrics 2026-03-22 10:51:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49506.1 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1340121
telemt_connections_bad_total 69499
telemt_connections_current 1839
telemt_connections_me_current 1839
telemt_handshake_timeouts_total 61392
telemt_upstream_connect_attempt_total 19055
telemt_upstream_connect_success_total 19054
telemt_upstream_connect_attempts_per_request{bucket="1"} 19054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12428
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 626
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 732908
telemt_me_route_drop_channel_closed_total 360
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1121917
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 395
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
telemt_desync_total 7319
telemt_desync_full_logged_total 2157
telemt_desync_suppressed_total 5162
telemt_desync_frames_bucket_total{bucket="1_2"} 2125
telemt_desync_frames_bucket_total{bucket="3_10"} 2761
telemt_desync_frames_bucket_total{bucket="gt_10"} 2433
telemt_pool_swap_total 54
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 213
telemt_me_draining_writers_reap_progress_total 17347
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16360
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15769
telemt_me_writer_teardown_success_total{mode="normal"} 17562
telemt_me_writer_teardown_noop_total 17349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 94.158836
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 213
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1119919
telemt_user_connections_current{user="hello"} 1839
telemt_user_octets_from_client{user="hello"} 18270142520 (17.02 GB)
telemt_user_octets_to_client{user="hello"} 353067863652 (328.82 GB)
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 62872.5 (17h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2149665
telemt_connections_bad_total 178034
telemt_connections_current 2170
telemt_connections_me_current 2170
telemt_handshake_timeouts_total 51508
telemt_upstream_connect_attempt_total 36767
telemt_upstream_connect_success_total 36270
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 36707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3176
telemt_me_reconnect_success_total 1423
telemt_me_reader_eof_total 1307
telemt_me_idle_close_by_peer_total 1307
telemt_me_route_drop_no_conn_total 1642670
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688814
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 44
telemt_desync_total 6959
telemt_desync_full_logged_total 3937
telemt_desync_suppressed_total 3022
telemt_desync_frames_bucket_total{bucket="1_2"} 1587
telemt_desync_frames_bucket_total{bucket="3_10"} 2722
telemt_desync_frames_bucket_total{bucket="gt_10"} 2650
telemt_pool_swap_total 63
telemt_pool_force_close_total 1783
telemt_me_writer_close_signal_drop_total 145
telemt_me_draining_writers_reap_progress_total 25242
telemt_me_writer_removed_unexpected_total 1273
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23767
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23459
telemt_me_writer_teardown_success_total{mode="normal"} 26509
telemt_me_writer_teardown_noop_total 25242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.574106
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 145
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1182
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1694767
telemt_user_connections_current{user="hello"} 2170
telemt_user_octets_from_client{user="hello"} 22895841938 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 459673451100 (428.10 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1291
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 137732.2 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11545202
telemt_connections_bad_total 975583
telemt_connections_current 5959
telemt_connections_me_current 5959
telemt_handshake_timeouts_total 313814
telemt_upstream_connect_attempt_total 50236
telemt_upstream_connect_success_total 50156
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2144
telemt_me_reconnect_success_total 1103
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1083
telemt_me_route_drop_no_conn_total 8454791
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9205919
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1024
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_warm_current 6
telemt_desync_total 38287
telemt_desync_full_logged_total 12366
telemt_desync_suppressed_total 25921
telemt_desync_frames_bucket_total{bucket="1_2"} 8623
telemt_desync_frames_bucket_total{bucket="3_10"} 14922
telemt_desync_frames_bucket_total{bucket="gt_10"} 14742
telemt_pool_swap_total 148
telemt_pool_force_close_total 4973
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 45804
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3919
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4639
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40831
telemt_me_writer_teardown_success_total{mode="normal"} 46272
telemt_me_writer_teardown_noop_total 45848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92120
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.531290
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92120
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 9195207
telemt_user_connections_current{user="hello"} 5959
telemt_user_octets_from_client{user="hello"} 142111538312 (132.35 GB)
telemt_user_octets_to_client{user="hello"} 2725426292192 (2.48 TB)
telemt_user_unique_ips_current{user="hello"} 2213
telemt_user_unique_ips_recent_window{user="hello"} 949
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 137734.2 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8980589
telemt_connections_bad_total 804303
telemt_connections_current 4462
telemt_connections_me_current 4462
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 274694
telemt_upstream_connect_attempt_total 56643
telemt_upstream_connect_success_total 56074
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 56335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3090
telemt_me_reconnect_success_total 1242
telemt_me_reader_eof_total 1131
telemt_me_idle_close_by_peer_total 1131
telemt_me_route_drop_no_conn_total 3630898
telemt_me_route_drop_channel_closed_total 370
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6689407
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1053
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
telemt_me_writers_warm_current 7
telemt_desync_total 30291
telemt_desync_full_logged_total 10250
telemt_desync_suppressed_total 20041
telemt_desync_frames_bucket_total{bucket="1_2"} 7387
telemt_desync_frames_bucket_total{bucket="3_10"} 11678
telemt_desync_frames_bucket_total{bucket="gt_10"} 11226
telemt_pool_swap_total 148
telemt_pool_force_close_total 4513
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 44256
telemt_me_writer_removed_unexpected_total 1166
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3855
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39743
telemt_me_writer_teardown_success_total{mode="normal"} 45316
telemt_me_writer_teardown_noop_total 44262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 66.123924
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1060
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6611029
telemt_user_connections_current{user="hello"} 4462
telemt_user_octets_from_client{user="hello"} 173517397059 (161.60 GB)
telemt_user_octets_to_client{user="hello"} 3047506702814 (2.77 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1795
telemt_user_unique_ips_recent_window{user="hello"} 655
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 137697.7 (38h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8518697
telemt_connections_bad_total 709557
telemt_connections_current 4543
telemt_connections_me_current 4543
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 274057
telemt_upstream_connect_attempt_total 60942
telemt_upstream_connect_success_total 60238
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28422
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3582
telemt_me_reconnect_success_total 1485
telemt_me_reader_eof_total 1372
telemt_me_idle_close_by_peer_total 1372
telemt_me_route_drop_no_conn_total 3596887
telemt_me_route_drop_channel_closed_total 239
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6392814
telemt_me_endpoint_quarantine_total 946
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1007
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29502
telemt_desync_full_logged_total 10047
telemt_desync_suppressed_total 19455
telemt_desync_frames_bucket_total{bucket="1_2"} 7121
telemt_desync_frames_bucket_total{bucket="3_10"} 11381
telemt_desync_frames_bucket_total{bucket="gt_10"} 11000
telemt_pool_swap_total 145
telemt_pool_force_close_total 4427
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 526
telemt_me_draining_writers_reap_progress_total 45056
telemt_me_writer_removed_unexpected_total 1397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42158
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 396
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40629
telemt_me_writer_teardown_success_total{mode="normal"} 46391
telemt_me_writer_teardown_noop_total 45073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.657032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 526
telemt_me_refill_failed_total 108
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 6384378
telemt_user_connections_current{user="hello"} 4543
telemt_user_octets_from_client{user="hello"} 158114932275 (147.26 GB)
telemt_user_octets_to_client{user="hello"} 2774010844419 (2.52 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1729
telemt_user_unique_ips_recent_window{user="hello"} 684
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 7977.6 (2h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3415192
telemt_connections_bad_total 230950
telemt_connections_current 6904
telemt_connections_me_current 6904
telemt_handshake_timeouts_total 51996
telemt_upstream_connect_attempt_total 9419
telemt_upstream_connect_success_total 8919
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 9266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2715
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_keepalive_timeout_total 374
telemt_me_reconnect_attempts_total 547
telemt_me_reconnect_success_total 220
telemt_me_reader_eof_total 152
telemt_me_idle_close_by_peer_total 152
telemt_me_route_drop_no_conn_total 7811658
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2844926
telemt_me_endpoint_quarantine_total 52
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 50
telemt_desync_total 4136
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 3057
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1776
telemt_pool_swap_total 6
telemt_pool_force_close_total 270
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 101
telemt_me_draining_writers_reap_progress_total 2103
telemt_me_writer_removed_unexpected_total 196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 355
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 106
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1833
telemt_me_writer_teardown_success_total{mode="normal"} 2281
telemt_me_writer_teardown_noop_total 2105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.837440
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 101
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 156
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 2848801
telemt_user_connections_current{user="hello"} 6904
telemt_user_octets_from_client{user="hello"} 14848269502 (13.83 GB)
telemt_user_octets_to_client{user="hello"} 84267825923 (78.48 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2495
telemt_user_unique_ips_recent_window{user="hello"} 1431
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 137704.4 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8210881
telemt_connections_bad_total 712106
telemt_connections_current 4594
telemt_connections_me_current 4594
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 168647
telemt_upstream_connect_attempt_total 86223
telemt_upstream_connect_success_total 85368
telemt_upstream_connect_fail_total 735
telemt_upstream_connect_attempts_per_request{bucket="1"} 86103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 735
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70649
telemt_me_reconnect_success_total 2176
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1912
telemt_me_route_drop_no_conn_total 3617826
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6487112
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1034
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
telemt_desync_total 32866
telemt_desync_full_logged_total 11340
telemt_desync_suppressed_total 21526
telemt_desync_frames_bucket_total{bucket="1_2"} 6715
telemt_desync_frames_bucket_total{bucket="3_10"} 12616
telemt_desync_frames_bucket_total{bucket="gt_10"} 13535
telemt_pool_swap_total 142
telemt_pool_force_close_total 4130
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47409
telemt_me_writer_removed_unexpected_total 1942
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44485
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 530
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43279
telemt_me_writer_teardown_success_total{mode="normal"} 49376
telemt_me_writer_teardown_noop_total 47410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96786
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.548510
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96786
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 4234
telemt_me_writer_restored_same_endpoint_total 1808
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6490659
telemt_user_connections_current{user="hello"} 4594
telemt_user_octets_from_client{user="hello"} 156599783607 (145.84 GB)
telemt_user_octets_to_client{user="hello"} 2572952502881 (2.34 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1861
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 74540.5 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7271320
telemt_connections_bad_total 273065
telemt_connections_current 4128
telemt_connections_me_current 4128
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2982941
telemt_upstream_connect_attempt_total 38793
telemt_upstream_connect_success_total 38512
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 38786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15947
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_reconnect_attempts_total 47696
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 2227527
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3592069
telemt_me_endpoint_quarantine_total 508
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 568
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 19424
telemt_desync_full_logged_total 6523
telemt_desync_suppressed_total 12901
telemt_desync_frames_bucket_total{bucket="1_2"} 3954
telemt_desync_frames_bucket_total{bucket="3_10"} 7459
telemt_desync_frames_bucket_total{bucket="gt_10"} 8011
telemt_pool_swap_total 78
telemt_pool_force_close_total 2395
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 26547
telemt_me_writer_removed_unexpected_total 1066
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2369
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25268
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24152
telemt_me_writer_teardown_success_total{mode="normal"} 27637
telemt_me_writer_teardown_noop_total 26553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.228872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1189
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3591017
telemt_user_connections_current{user="hello"} 4128
telemt_user_octets_from_client{user="hello"} 85293422592 (79.44 GB)
telemt_user_octets_to_client{user="hello"} 1464372667258 (1.33 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1704
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 55511.1 (15h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571131
telemt_connections_bad_total 4113
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10513
telemt_upstream_connect_attempt_total 29133
telemt_upstream_connect_success_total 29066
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1211
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 187635
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517458
telemt_me_endpoint_quarantine_total 498
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 471
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 43
telemt_desync_total 2724
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1946
telemt_desync_frames_bucket_total{bucket="1_2"} 756
telemt_desync_frames_bucket_total{bucket="3_10"} 1055
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 58
telemt_pool_force_close_total 1408
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 23685
telemt_me_writer_removed_unexpected_total 498
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22445
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1332
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22277
telemt_me_writer_teardown_success_total{mode="normal"} 24200
telemt_me_writer_teardown_noop_total 23685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.565159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 519390
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 9997953461 (9.31 GB)
telemt_user_octets_to_client{user="hello"} 246512620107 (229.58 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 137708.7 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9986614
telemt_connections_bad_total 1169725
telemt_connections_current 5838
telemt_connections_me_current 5838
telemt_handshake_timeouts_total 266219
telemt_upstream_connect_attempt_total 52774
telemt_upstream_connect_success_total 52574
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2039
telemt_me_reconnect_success_total 1085
telemt_me_reader_eof_total 1052
telemt_me_idle_close_by_peer_total 1052
telemt_me_route_drop_no_conn_total 2874070
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7439894
telemt_me_endpoint_quarantine_total 964
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1036
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 30229
telemt_desync_full_logged_total 9919
telemt_desync_suppressed_total 20310
telemt_desync_frames_bucket_total{bucket="1_2"} 7410
telemt_desync_frames_bucket_total{bucket="3_10"} 11061
telemt_desync_frames_bucket_total{bucket="gt_10"} 11758
telemt_pool_swap_total 152
telemt_pool_force_close_total 4117
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 47586
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43469
telemt_me_writer_teardown_success_total{mode="normal"} 48629
telemt_me_writer_teardown_noop_total 47588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.189668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7411746
telemt_user_connections_current{user="hello"} 5838
telemt_user_octets_from_client{user="hello"} 143474728876 (133.62 GB)
telemt_user_octets_to_client{user="hello"} 3445606531596 (3.13 TB)
telemt_user_unique_ips_current{user="hello"} 2164
telemt_user_unique_ips_recent_window{user="hello"} 796
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 137705.4 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8685655
telemt_connections_bad_total 983704
telemt_connections_current 5048
telemt_connections_me_current 5048
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 222801
telemt_upstream_connect_attempt_total 77273
telemt_upstream_connect_success_total 76725
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 77204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_reconnect_attempts_total 6599
telemt_me_reconnect_success_total 1558
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1381
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3133581
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6636918
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1039
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 29434
telemt_desync_full_logged_total 9705
telemt_desync_suppressed_total 19729
telemt_desync_frames_bucket_total{bucket="1_2"} 7252
telemt_desync_frames_bucket_total{bucket="3_10"} 10892
telemt_desync_frames_bucket_total{bucket="gt_10"} 11290
telemt_pool_swap_total 149
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 498
telemt_me_draining_writers_reap_progress_total 46268
telemt_me_writer_removed_unexpected_total 1400
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4493
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43238
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 299
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42218
telemt_me_writer_teardown_success_total{mode="normal"} 47731
telemt_me_writer_teardown_noop_total 46272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.656296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 498
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1213
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6645009
telemt_user_connections_current{user="hello"} 5048
telemt_user_octets_from_client{user="hello"} 119965348609 (111.73 GB)
telemt_user_octets_to_client{user="hello"} 2785265466531 (2.53 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1975
telemt_user_unique_ips_recent_window{user="hello"} 691
```