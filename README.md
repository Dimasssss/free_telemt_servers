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

# Server Metrics 2026-03-22 09:29:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44595.6 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120754
telemt_connections_bad_total 61219
telemt_connections_current 1700
telemt_connections_me_current 1700
telemt_handshake_timeouts_total 51267
telemt_upstream_connect_attempt_total 17496
telemt_upstream_connect_success_total 17495
telemt_upstream_connect_attempts_per_request{bucket="1"} 17495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 607827
telemt_me_route_drop_channel_closed_total 235
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932620
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 315
telemt_me_single_endpoint_shadow_rotate_total 359
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6632
telemt_desync_full_logged_total 1907
telemt_desync_suppressed_total 4725
telemt_desync_frames_bucket_total{bucket="1_2"} 1970
telemt_desync_frames_bucket_total{bucket="3_10"} 2494
telemt_desync_frames_bucket_total{bucket="gt_10"} 2168
telemt_pool_swap_total 49
telemt_pool_force_close_total 1394
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 167
telemt_me_draining_writers_reap_progress_total 15889
telemt_me_writer_removed_unexpected_total 263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14998
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14495
telemt_me_writer_teardown_success_total{mode="normal"} 16104
telemt_me_writer_teardown_noop_total 15891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31995
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.617230
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31995
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 167
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 930919
telemt_user_connections_current{user="hello"} 1700
telemt_user_octets_from_client{user="hello"} 14678513868 (13.67 GB)
telemt_user_octets_to_client{user="hello"} 297691428060 (277.25 GB)
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 57961.9 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1681245
telemt_connections_bad_total 157241
telemt_connections_current 2382
telemt_connections_me_current 2382
telemt_handshake_timeouts_total 45295
telemt_upstream_connect_attempt_total 34549
telemt_upstream_connect_success_total 34101
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 34495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 1140
telemt_me_reader_eof_total 1035
telemt_me_idle_close_by_peer_total 1035
telemt_me_route_drop_no_conn_total 893579
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1280871
telemt_me_endpoint_quarantine_total 505
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 459
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 5740
telemt_desync_full_logged_total 3302
telemt_desync_suppressed_total 2438
telemt_desync_frames_bucket_total{bucket="1_2"} 1280
telemt_desync_frames_bucket_total{bucket="3_10"} 2240
telemt_desync_frames_bucket_total{bucket="gt_10"} 2220
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 23447
telemt_me_writer_removed_unexpected_total 1003
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22088
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21837
telemt_me_writer_teardown_success_total{mode="normal"} 24441
telemt_me_writer_teardown_noop_total 23447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47888
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.217486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47888
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 921
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1287022
telemt_user_connections_current{user="hello"} 2382
telemt_user_octets_from_client{user="hello"} 18996881306 (17.69 GB)
telemt_user_octets_to_client{user="hello"} 412104258692 (383.80 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1401
telemt_user_unique_ips_recent_window{user="hello"} 642
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 132821.9 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10317056
telemt_connections_bad_total 918574
telemt_connections_current 4572
telemt_connections_me_current 4572
telemt_handshake_timeouts_total 299460
telemt_upstream_connect_attempt_total 48808
telemt_upstream_connect_success_total 48728
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1976
telemt_me_reconnect_success_total 1032
telemt_me_reader_eof_total 1029
telemt_me_idle_close_by_peer_total 1028
telemt_me_route_drop_no_conn_total 6314927
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8124466
telemt_me_endpoint_quarantine_total 843
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 991
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
telemt_me_writers_active_current 43
telemt_desync_total 35019
telemt_desync_full_logged_total 11423
telemt_desync_suppressed_total 23596
telemt_desync_frames_bucket_total{bucket="1_2"} 7764
telemt_desync_frames_bucket_total{bucket="3_10"} 13626
telemt_desync_frames_bucket_total{bucket="gt_10"} 13629
telemt_pool_swap_total 143
telemt_pool_force_close_total 4779
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 44541
telemt_me_writer_removed_unexpected_total 989
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3763
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41224
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4460
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39762
telemt_me_writer_teardown_success_total{mode="normal"} 44987
telemt_me_writer_teardown_noop_total 44585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.032919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 8114319
telemt_user_connections_current{user="hello"} 4572
telemt_user_octets_from_client{user="hello"} 130883235080 (121.89 GB)
telemt_user_octets_to_client{user="hello"} 2619373574732 (2.38 TB)
telemt_user_unique_ips_current{user="hello"} 1726
telemt_user_unique_ips_recent_window{user="hello"} 722
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 132823.5 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8309284
telemt_connections_bad_total 747741
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 264181
telemt_upstream_connect_attempt_total 54880
telemt_upstream_connect_success_total 54389
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 54636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26614
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2981
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 1069
telemt_me_idle_close_by_peer_total 1069
telemt_me_route_drop_no_conn_total 2880760
telemt_me_route_drop_channel_closed_total 337
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6153566
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1021
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
telemt_me_writers_active_current 90
telemt_desync_total 28268
telemt_desync_full_logged_total 9597
telemt_desync_suppressed_total 18671
telemt_desync_frames_bucket_total{bucket="1_2"} 6837
telemt_desync_frames_bucket_total{bucket="3_10"} 10938
telemt_desync_frames_bucket_total{bucket="gt_10"} 10493
telemt_pool_swap_total 144
telemt_pool_force_close_total 4337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 42736
telemt_me_writer_removed_unexpected_total 1087
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4075
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38399
telemt_me_writer_teardown_success_total{mode="normal"} 43716
telemt_me_writer_teardown_noop_total 42742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86458
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.030673
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86458
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 981
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6075887
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 164782240587 (153.47 GB)
telemt_user_octets_to_client{user="hello"} 2889031209126 (2.63 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1972
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 132787.3 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7967250
telemt_connections_bad_total 666093
telemt_connections_current 3871
telemt_connections_me_current 3871
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 262594
telemt_upstream_connect_attempt_total 59570
telemt_upstream_connect_success_total 58880
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1347
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3409
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1340
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 3243844
telemt_me_route_drop_channel_closed_total 209
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5941965
telemt_me_endpoint_quarantine_total 921
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 974
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 27852
telemt_desync_full_logged_total 9480
telemt_desync_suppressed_total 18372
telemt_desync_frames_bucket_total{bucket="1_2"} 6729
telemt_desync_frames_bucket_total{bucket="3_10"} 10697
telemt_desync_frames_bucket_total{bucket="gt_10"} 10426
telemt_pool_swap_total 140
telemt_pool_force_close_total 4234
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 43826
telemt_me_writer_removed_unexpected_total 1366
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4100
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41064
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 376
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39592
telemt_me_writer_teardown_success_total{mode="normal"} 45164
telemt_me_writer_teardown_noop_total 43838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.056495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 5934606
telemt_user_connections_current{user="hello"} 3871
telemt_user_octets_from_client{user="hello"} 151470572779 (141.07 GB)
telemt_user_octets_to_client{user="hello"} 2624645676071 (2.39 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1510
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 3067.3 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235797
telemt_connections_bad_total 99792
telemt_connections_current 6059
telemt_connections_me_current 6059
telemt_handshake_timeouts_total 15289
telemt_upstream_connect_attempt_total 7826
telemt_upstream_connect_success_total 7424
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 7760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2662
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 309
telemt_me_reconnect_success_total 108
telemt_me_reader_eof_total 57
telemt_me_idle_close_by_peer_total 57
telemt_me_route_drop_no_conn_total 2577409
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1015449
telemt_me_endpoint_quarantine_total 18
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 30
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
telemt_me_writers_active_current 44
telemt_desync_total 1628
telemt_desync_full_logged_total 424
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 311
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 683
telemt_pool_swap_total 2
telemt_pool_force_close_total 95
telemt_me_writer_close_signal_drop_total 44
telemt_me_draining_writers_reap_progress_total 825
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 769
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 730
telemt_me_writer_teardown_success_total{mode="normal"} 926
telemt_me_writer_teardown_noop_total 825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.002588
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 44
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1021517
telemt_user_connections_current{user="hello"} 6059
telemt_user_octets_from_client{user="hello"} 6483910002 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 31642106631 (29.47 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2247
telemt_user_unique_ips_recent_window{user="hello"} 1329
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 132794.0 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7597037
telemt_connections_bad_total 679186
telemt_connections_current 4654
telemt_connections_me_current 4654
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 156144
telemt_upstream_connect_attempt_total 75704
telemt_upstream_connect_success_total 74878
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 443
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70458
telemt_me_reconnect_success_total 2076
telemt_me_reader_eof_total 1821
telemt_me_idle_close_by_peer_total 1820
telemt_me_route_drop_no_conn_total 3048033
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5975275
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1002
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
telemt_me_writers_active_current 43
telemt_desync_total 30301
telemt_desync_full_logged_total 10478
telemt_desync_suppressed_total 19823
telemt_desync_frames_bucket_total{bucket="1_2"} 6089
telemt_desync_frames_bucket_total{bucket="3_10"} 11640
telemt_desync_frames_bucket_total{bucket="gt_10"} 12572
telemt_pool_swap_total 138
telemt_pool_force_close_total 3996
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 477
telemt_me_draining_writers_reap_progress_total 46073
telemt_me_writer_removed_unexpected_total 1850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42077
telemt_me_writer_teardown_success_total{mode="normal"} 47950
telemt_me_writer_teardown_noop_total 46074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94024
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.552200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94024
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 477
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 5973128
telemt_user_connections_current{user="hello"} 4654
telemt_user_octets_from_client{user="hello"} 149313685739 (139.06 GB)
telemt_user_octets_to_client{user="hello"} 2446331859527 (2.22 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1853
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 69630.3 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6257699
telemt_connections_bad_total 244533
telemt_connections_current 4047
telemt_connections_me_current 4047
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2523826
telemt_upstream_connect_attempt_total 37081
telemt_upstream_connect_success_total 36821
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 37074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_reconnect_attempts_total 47470
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 1626813
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3114743
telemt_me_endpoint_quarantine_total 481
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 53
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 53
telemt_me_single_endpoint_shadow_rotate_total 533
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 16998
telemt_desync_full_logged_total 5744
telemt_desync_suppressed_total 11254
telemt_desync_frames_bucket_total{bucket="1_2"} 3357
telemt_desync_frames_bucket_total{bucket="3_10"} 6508
telemt_desync_frames_bucket_total{bucket="gt_10"} 7133
telemt_pool_swap_total 74
telemt_pool_force_close_total 2246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 25089
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22843
telemt_me_writer_teardown_success_total{mode="normal"} 26094
telemt_me_writer_teardown_noop_total 25095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51189
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.758449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51189
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1114
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3115347
telemt_user_connections_current{user="hello"} 4047
telemt_user_octets_from_client{user="hello"} 77773230172 (72.43 GB)
telemt_user_octets_to_client{user="hello"} 1336700444106 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1546
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50600.5 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475215
telemt_connections_bad_total 3683
telemt_connections_current 901
telemt_connections_me_current 901
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8994
telemt_upstream_connect_attempt_total 26923
telemt_upstream_connect_success_total 26860
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 26918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 447
telemt_me_reader_eof_total 447
telemt_me_idle_close_by_peer_total 447
telemt_me_route_drop_no_conn_total 154546
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428953
telemt_me_endpoint_quarantine_total 475
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 433
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 1994
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1405
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 781
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 54
telemt_pool_force_close_total 1271
telemt_me_writer_close_signal_drop_total 55
telemt_me_draining_writers_reap_progress_total 21731
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1589
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20589
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1220
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20460
telemt_me_writer_teardown_success_total{mode="normal"} 22178
telemt_me_writer_teardown_noop_total 21731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.101726
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 55
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 396
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 431044
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 8576873205 (7.99 GB)
telemt_user_octets_to_client{user="hello"} 214778266607 (200.03 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 132798.4 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9344790
telemt_connections_bad_total 1084834
telemt_connections_current 5006
telemt_connections_me_current 5006
telemt_handshake_timeouts_total 255605
telemt_upstream_connect_attempt_total 51375
telemt_upstream_connect_success_total 51178
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 51329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1021
telemt_me_idle_close_by_peer_total 1021
telemt_me_route_drop_no_conn_total 2643414
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6932555
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1008
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
telemt_desync_total 28047
telemt_desync_full_logged_total 9185
telemt_desync_suppressed_total 18862
telemt_desync_frames_bucket_total{bucket="1_2"} 6927
telemt_desync_frames_bucket_total{bucket="3_10"} 10231
telemt_desync_frames_bucket_total{bucket="gt_10"} 10889
telemt_pool_swap_total 147
telemt_pool_force_close_total 3960
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 46341
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43633
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42381
telemt_me_writer_teardown_success_total{mode="normal"} 47353
telemt_me_writer_teardown_noop_total 46343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.890288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 6905216
telemt_user_connections_current{user="hello"} 5006
telemt_user_octets_from_client{user="hello"} 133862331028 (124.67 GB)
telemt_user_octets_to_client{user="hello"} 3236744718020 (2.94 TB)
telemt_user_unique_ips_current{user="hello"} 1867
telemt_user_unique_ips_recent_window{user="hello"} 643
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 132795.2 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8129574
telemt_connections_bad_total 906503
telemt_connections_current 4512
telemt_connections_me_current 4512
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 214048
telemt_upstream_connect_attempt_total 75818
telemt_upstream_connect_success_total 75281
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 75749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6496
telemt_me_reconnect_success_total 1512
telemt_me_reader_eof_total 1343
telemt_me_idle_close_by_peer_total 1343
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2844312
telemt_me_route_drop_channel_closed_total 244
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6191105
telemt_me_endpoint_quarantine_total 1038
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1006
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
telemt_me_writers_active_current 53
telemt_desync_total 26895
telemt_desync_full_logged_total 8937
telemt_desync_suppressed_total 17958
telemt_desync_frames_bucket_total{bucket="1_2"} 6615
telemt_desync_frames_bucket_total{bucket="3_10"} 9873
telemt_desync_frames_bucket_total{bucket="gt_10"} 10407
telemt_pool_swap_total 144
telemt_pool_force_close_total 3885
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 481
telemt_me_draining_writers_reap_progress_total 44980
telemt_me_writer_removed_unexpected_total 1360
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42041
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3605
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41095
telemt_me_writer_teardown_success_total{mode="normal"} 46402
telemt_me_writer_teardown_noop_total 44984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.391862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 481
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6199798
telemt_user_connections_current{user="hello"} 4512
telemt_user_octets_from_client{user="hello"} 113350253461 (105.57 GB)
telemt_user_octets_to_client{user="hello"} 2644979592491 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1751
telemt_user_unique_ips_recent_window{user="hello"} 623
```