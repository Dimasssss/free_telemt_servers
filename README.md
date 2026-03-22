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

# Server Metrics 2026-03-22 06:36:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 34177.9 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659380
telemt_connections_bad_total 40972
telemt_connections_current 1411
telemt_connections_me_current 1411
telemt_handshake_timeouts_total 32247
telemt_upstream_connect_attempt_total 13977
telemt_upstream_connect_success_total 13976
telemt_upstream_connect_attempts_per_request{bucket="1"} 13976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 371
telemt_me_reconnect_success_total 220
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 238131
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545968
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_shadow_rotate_total 280
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
telemt_me_writers_active_current 48
telemt_desync_total 4604
telemt_desync_full_logged_total 1282
telemt_desync_suppressed_total 3322
telemt_desync_frames_bucket_total{bucket="1_2"} 1517
telemt_desync_frames_bucket_total{bucket="3_10"} 1722
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 37
telemt_pool_force_close_total 988
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 12636
telemt_me_writer_removed_unexpected_total 213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11970
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 978
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11648
telemt_me_writer_teardown_success_total{mode="normal"} 12836
telemt_me_writer_teardown_noop_total 12637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.574788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 544863
telemt_user_connections_current{user="hello"} 1411
telemt_user_octets_from_client{user="hello"} 7605042212 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 190790646088 (177.69 GB)
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47544.3 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123987
telemt_connections_bad_total 105755
telemt_connections_current 1604
telemt_connections_me_current 1604
telemt_handshake_timeouts_total 36671
telemt_upstream_connect_attempt_total 25135
telemt_upstream_connect_success_total 24775
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 25090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12168
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 723
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_route_drop_no_conn_total 415276
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855686
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 382
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
telemt_desync_total 3607
telemt_desync_full_logged_total 2109
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 763
telemt_desync_frames_bucket_total{bucket="3_10"} 1394
telemt_desync_frames_bucket_total{bucket="gt_10"} 1450
telemt_pool_swap_total 50
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 19679
telemt_me_writer_removed_unexpected_total 613
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18572
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18326
telemt_me_writer_teardown_success_total{mode="normal"} 20276
telemt_me_writer_teardown_noop_total 19679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39955
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.073209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39955
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 552
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 857321
telemt_user_connections_current{user="hello"} 1604
telemt_user_octets_from_client{user="hello"} 13920478483 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 319300682362 (297.37 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 122404.2 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8672733
telemt_connections_bad_total 783382
telemt_connections_current 4404
telemt_connections_me_current 4404
telemt_handshake_timeouts_total 276577
telemt_upstream_connect_attempt_total 45352
telemt_upstream_connect_success_total 45274
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1739
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 4764171
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6884678
telemt_me_endpoint_quarantine_total 778
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 921
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
telemt_me_writers_active_current 49
telemt_desync_total 29423
telemt_desync_full_logged_total 9758
telemt_desync_suppressed_total 19665
telemt_desync_frames_bucket_total{bucket="1_2"} 6372
telemt_desync_frames_bucket_total{bucket="3_10"} 11470
telemt_desync_frames_bucket_total{bucket="gt_10"} 11581
telemt_pool_swap_total 132
telemt_pool_force_close_total 4360
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 41393
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3434
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38336
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 257
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37033
telemt_me_writer_teardown_success_total{mode="normal"} 41770
telemt_me_writer_teardown_noop_total 41437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.760202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6875761
telemt_user_connections_current{user="hello"} 4404
telemt_user_octets_from_client{user="hello"} 116288805792 (108.30 GB)
telemt_user_octets_to_client{user="hello"} 2346888536824 (2.13 TB)
telemt_user_unique_ips_current{user="hello"} 1833
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 122405.7 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7155916
telemt_connections_bad_total 632581
telemt_connections_current 3748
telemt_connections_me_current 3748
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 237871
telemt_upstream_connect_attempt_total 49289
telemt_upstream_connect_success_total 48884
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 49092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2070
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 926
telemt_me_route_drop_no_conn_total 2419467
telemt_me_route_drop_channel_closed_total 295
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5307832
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
telemt_desync_total 24575
telemt_desync_full_logged_total 8442
telemt_desync_suppressed_total 16133
telemt_desync_frames_bucket_total{bucket="1_2"} 5885
telemt_desync_frames_bucket_total{bucket="3_10"} 9539
telemt_desync_frames_bucket_total{bucket="gt_10"} 9151
telemt_pool_swap_total 133
telemt_pool_force_close_total 3961
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 403
telemt_me_draining_writers_reap_progress_total 39816
telemt_me_writer_removed_unexpected_total 903
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35855
telemt_me_writer_teardown_success_total{mode="normal"} 40648
telemt_me_writer_teardown_noop_total 39822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80470
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.060242
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80470
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 403
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5229094
telemt_user_connections_current{user="hello"} 3748
telemt_user_octets_from_client{user="hello"} 150464681237 (140.13 GB)
telemt_user_octets_to_client{user="hello"} 2526803312667 (2.30 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1494
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 122371.4 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6923682
telemt_connections_bad_total 578328
telemt_connections_current 3163
telemt_connections_me_current 3163
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 232818
telemt_upstream_connect_attempt_total 55783
telemt_upstream_connect_success_total 55181
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2587
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 2498849
telemt_me_route_drop_channel_closed_total 156
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5147758
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
telemt_desync_total 24434
telemt_desync_full_logged_total 8280
telemt_desync_suppressed_total 16154
telemt_desync_frames_bucket_total{bucket="1_2"} 5922
telemt_desync_frames_bucket_total{bucket="3_10"} 9374
telemt_desync_frames_bucket_total{bucket="gt_10"} 9138
telemt_pool_swap_total 131
telemt_pool_force_close_total 3832
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 40794
telemt_me_writer_removed_unexpected_total 1032
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3538
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38300
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 250
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36962
telemt_me_writer_teardown_success_total{mode="normal"} 41838
telemt_me_writer_teardown_noop_total 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82644
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.068110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82644
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5141907
telemt_user_connections_current{user="hello"} 3163
telemt_user_octets_from_client{user="hello"} 140134883243 (130.51 GB)
telemt_user_octets_to_client{user="hello"} 2340822545619 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 122408.8 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22160970
telemt_connections_bad_total 1877202
telemt_connections_current 5017
telemt_connections_me_current 5017
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 665821
telemt_upstream_connect_attempt_total 225429
telemt_upstream_connect_success_total 206266
telemt_upstream_connect_fail_total 17228
telemt_upstream_connect_attempts_per_request{bucket="1"} 223494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17228
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66346
telemt_me_reconnect_success_total 2598
telemt_me_reader_eof_total 1634
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 42018870
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17819894
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 959
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
telemt_me_writers_active_current 45
telemt_desync_total 34368
telemt_desync_full_logged_total 10339
telemt_desync_suppressed_total 24029
telemt_desync_frames_bucket_total{bucket="1_2"} 7599
telemt_desync_frames_bucket_total{bucket="3_10"} 15185
telemt_desync_frames_bucket_total{bucket="gt_10"} 11584
telemt_pool_swap_total 126
telemt_pool_force_close_total 4019
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 909
telemt_me_draining_writers_reap_progress_total 38330
telemt_me_writer_removed_unexpected_total 2409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5194
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35295
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3448
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34311
telemt_me_writer_teardown_success_total{mode="normal"} 40489
telemt_me_writer_teardown_noop_total 38360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.688152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 909
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1767
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17972520
telemt_user_connections_current{user="hello"} 5018
telemt_user_octets_from_client{user="hello"} 266604179433 (248.29 GB)
telemt_user_octets_to_client{user="hello"} 1372731096199 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1840
telemt_user_unique_ips_recent_window{user="hello"} 864
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 122376.5 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6651288
telemt_connections_bad_total 620206
telemt_connections_current 3462
telemt_connections_me_current 3462
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 138418
telemt_upstream_connect_attempt_total 64390
telemt_upstream_connect_success_total 63651
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 64284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26747
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69990
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1685
telemt_me_idle_close_by_peer_total 1684
telemt_me_route_drop_no_conn_total 2548522
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5194745
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
telemt_desync_total 25953
telemt_desync_full_logged_total 9047
telemt_desync_suppressed_total 16906
telemt_desync_frames_bucket_total{bucket="1_2"} 5156
telemt_desync_frames_bucket_total{bucket="3_10"} 9979
telemt_desync_frames_bucket_total{bucket="gt_10"} 10818
telemt_pool_swap_total 127
telemt_pool_force_close_total 3642
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 43017
telemt_me_writer_removed_unexpected_total 1718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4312
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39375
telemt_me_writer_teardown_success_total{mode="normal"} 44770
telemt_me_writer_teardown_noop_total 43018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.901515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1594
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5186469
telemt_user_connections_current{user="hello"} 3462
telemt_user_octets_from_client{user="hello"} 133374759060 (124.21 GB)
telemt_user_octets_to_client{user="hello"} 2168763185202 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1482
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59212.3 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4784523
telemt_connections_bad_total 198584
telemt_connections_current 3089
telemt_connections_me_current 3089
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1882859
telemt_upstream_connect_attempt_total 33223
telemt_upstream_connect_success_total 32999
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 33216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_reconnect_attempts_total 46184
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 753
telemt_me_idle_close_by_peer_total 753
telemt_me_route_drop_no_conn_total 1183110
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2383489
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12726
telemt_desync_full_logged_total 4399
telemt_desync_suppressed_total 8327
telemt_desync_frames_bucket_total{bucket="1_2"} 2468
telemt_desync_frames_bucket_total{bucket="3_10"} 4867
telemt_desync_frames_bucket_total{bucket="gt_10"} 5391
telemt_pool_swap_total 64
telemt_pool_force_close_total 1877
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 164
telemt_me_draining_writers_reap_progress_total 21686
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20699
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19809
telemt_me_writer_teardown_success_total{mode="normal"} 22539
telemt_me_writer_teardown_noop_total 21688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44227
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.767059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44227
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 164
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2385544
telemt_user_connections_current{user="hello"} 3089
telemt_user_octets_from_client{user="hello"} 62245528528 (57.97 GB)
telemt_user_octets_to_client{user="hello"} 1058073997006 (985.41 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1338
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40183.0 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297863
telemt_connections_bad_total 2066
telemt_connections_current 597
telemt_connections_me_current 597
telemt_handshake_timeouts_total 7106
telemt_upstream_connect_attempt_total 19328
telemt_upstream_connect_success_total 19280
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 19324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 828
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 87106
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268340
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 49
telemt_desync_total 1324
telemt_desync_full_logged_total 371
telemt_desync_suppressed_total 953
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 44
telemt_pool_force_close_total 986
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17490
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1126
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16638
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16504
telemt_me_writer_teardown_success_total{mode="normal"} 17764
telemt_me_writer_teardown_noop_total 17490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.365574
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 267928
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 4428257256 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 156056031160 (145.34 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 122380.7 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8072493
telemt_connections_bad_total 820435
telemt_connections_current 3687
telemt_connections_me_current 3687
telemt_handshake_timeouts_total 227628
telemt_upstream_connect_attempt_total 48098
telemt_upstream_connect_success_total 47923
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 48059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1765
telemt_me_reconnect_success_total 946
telemt_me_reader_eof_total 930
telemt_me_idle_close_by_peer_total 930
telemt_me_route_drop_no_conn_total 2282443
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6027852
telemt_me_endpoint_quarantine_total 872
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 937
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
telemt_me_writers_active_current 46
telemt_desync_total 23755
telemt_desync_full_logged_total 7823
telemt_desync_suppressed_total 15932
telemt_desync_frames_bucket_total{bucket="1_2"} 5931
telemt_desync_frames_bucket_total{bucket="3_10"} 8658
telemt_desync_frames_bucket_total{bucket="gt_10"} 9166
telemt_pool_swap_total 135
telemt_pool_force_close_total 3602
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 425
telemt_me_draining_writers_reap_progress_total 43428
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3396
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40952
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3511
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39826
telemt_me_writer_teardown_success_total{mode="normal"} 44348
telemt_me_writer_teardown_noop_total 43430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87778
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.219166
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87778
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 425
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 6002020
telemt_user_connections_current{user="hello"} 3687
telemt_user_octets_from_client{user="hello"} 117652382888 (109.57 GB)
telemt_user_octets_to_client{user="hello"} 2816425599080 (2.56 TB)
telemt_user_unique_ips_current{user="hello"} 1457
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 122377.5 (33h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7053789
telemt_connections_bad_total 714520
telemt_connections_current 3705
telemt_connections_me_current 3705
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 188887
telemt_upstream_connect_attempt_total 63871
telemt_upstream_connect_success_total 63383
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 63808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_reconnect_attempts_total 5866
telemt_me_reconnect_success_total 1314
telemt_me_reader_eof_total 1181
telemt_me_idle_close_by_peer_total 1181
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2341721
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5390669
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
telemt_desync_total 22713
telemt_desync_full_logged_total 7543
telemt_desync_suppressed_total 15170
telemt_desync_frames_bucket_total{bucket="1_2"} 5673
telemt_desync_frames_bucket_total{bucket="3_10"} 8305
telemt_desync_frames_bucket_total{bucket="gt_10"} 8735
telemt_pool_swap_total 133
telemt_pool_force_close_total 3547
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 41893
telemt_me_writer_removed_unexpected_total 1193
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3949
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38346
telemt_me_writer_teardown_success_total{mode="normal"} 43147
telemt_me_writer_teardown_noop_total 41897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.072045
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5392907
telemt_user_connections_current{user="hello"} 3705
telemt_user_octets_from_client{user="hello"} 100592348525 (93.68 GB)
telemt_user_octets_to_client{user="hello"} 2342674485928 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1525
telemt_user_unique_ips_recent_window{user="hello"} 510
```