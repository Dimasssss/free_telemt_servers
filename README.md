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

# Server Metrics 2026-03-22 11:27:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51648.2 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1448983
telemt_connections_bad_total 72279
telemt_connections_current 1640
telemt_connections_me_current 1640
telemt_handshake_timeouts_total 66267
telemt_upstream_connect_attempt_total 19877
telemt_upstream_connect_success_total 19876
telemt_upstream_connect_attempts_per_request{bucket="1"} 19876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 679
telemt_me_reconnect_success_total 331
telemt_me_reader_eof_total 326
telemt_me_idle_close_by_peer_total 326
telemt_me_route_drop_no_conn_total 865205
telemt_me_route_drop_channel_closed_total 433
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218686
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_me_writers_active_current 47
telemt_desync_total 7684
telemt_desync_full_logged_total 2294
telemt_desync_suppressed_total 5390
telemt_desync_frames_bucket_total{bucket="1_2"} 2210
telemt_desync_frames_bucket_total{bucket="3_10"} 2876
telemt_desync_frames_bucket_total{bucket="gt_10"} 2598
telemt_pool_swap_total 57
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 249
telemt_me_draining_writers_reap_progress_total 18087
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17042
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1634
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16418
telemt_me_writer_teardown_success_total{mode="normal"} 18317
telemt_me_writer_teardown_noop_total 18089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 113.489601
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 249
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1216190
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 19609775444 (18.26 GB)
telemt_user_octets_to_client{user="hello"} 377018575332 (351.13 GB)
telemt_user_unique_ips_current{user="hello"} 649
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 65014.6 (18h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371976
telemt_connections_bad_total 195023
telemt_connections_current 2420
telemt_connections_me_current 2420
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 54781
telemt_upstream_connect_attempt_total 43563
telemt_upstream_connect_success_total 43050
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 43503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3359
telemt_me_reconnect_success_total 1491
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1374
telemt_me_route_drop_no_conn_total 1998626
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1870751
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 513
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
telemt_me_writers_active_current 78
telemt_me_writers_warm_current 8
telemt_desync_total 7477
telemt_desync_full_logged_total 4217
telemt_desync_suppressed_total 3260
telemt_desync_frames_bucket_total{bucket="1_2"} 1709
telemt_desync_frames_bucket_total{bucket="3_10"} 2941
telemt_desync_frames_bucket_total{bucket="gt_10"} 2827
telemt_pool_swap_total 65
telemt_pool_force_close_total 1814
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 25839
telemt_me_writer_removed_unexpected_total 1337
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24307
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24025
telemt_me_writer_teardown_success_total{mode="normal"} 27173
telemt_me_writer_teardown_noop_total 25839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.918182
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1882656
telemt_user_connections_current{user="hello"} 2420
telemt_user_octets_from_client{user="hello"} 23969953851 (22.32 GB)
telemt_user_octets_to_client{user="hello"} 475467202694 (442.81 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1457
telemt_user_unique_ips_recent_window{user="hello"} 863
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 139874.3 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12199945
telemt_connections_bad_total 1056800
telemt_connections_current 4509
telemt_connections_me_current 4509
telemt_handshake_timeouts_total 320837
telemt_upstream_connect_attempt_total 50859
telemt_upstream_connect_success_total 50779
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2190
telemt_me_reconnect_success_total 1118
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1098
telemt_me_route_drop_no_conn_total 9667889
telemt_me_route_drop_channel_closed_total 106
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9736644
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1042
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
telemt_me_writers_active_current 44
telemt_desync_total 39806
telemt_desync_full_logged_total 12814
telemt_desync_suppressed_total 26992
telemt_desync_frames_bucket_total{bucket="1_2"} 8968
telemt_desync_frames_bucket_total{bucket="3_10"} 15538
telemt_desync_frames_bucket_total{bucket="gt_10"} 15300
telemt_pool_swap_total 151
telemt_pool_force_close_total 5094
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 46400
telemt_me_writer_removed_unexpected_total 1059
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42869
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41306
telemt_me_writer_teardown_success_total{mode="normal"} 46857
telemt_me_writer_teardown_noop_total 46444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.035188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 973
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 9725662
telemt_user_connections_current{user="hello"} 4509
telemt_user_octets_from_client{user="hello"} 145377873252 (135.39 GB)
telemt_user_octets_to_client{user="hello"} 2766856652832 (2.52 TB)
telemt_user_unique_ips_current{user="hello"} 1737
telemt_user_unique_ips_recent_window{user="hello"} 973
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 139875.8 (38h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9216340
telemt_connections_bad_total 825490
telemt_connections_current 4571
telemt_connections_me_current 4571
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 280999
telemt_upstream_connect_attempt_total 57493
telemt_upstream_connect_success_total 56913
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 57179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3221
telemt_me_reconnect_success_total 1305
telemt_me_reader_eof_total 1196
telemt_me_idle_close_by_peer_total 1196
telemt_me_route_drop_no_conn_total 3738406
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6875242
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1070
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
telemt_me_writers_active_current 43
telemt_desync_total 31146
telemt_desync_full_logged_total 10527
telemt_desync_suppressed_total 20619
telemt_desync_frames_bucket_total{bucket="1_2"} 7656
telemt_desync_frames_bucket_total{bucket="3_10"} 11996
telemt_desync_frames_bucket_total{bucket="gt_10"} 11494
telemt_pool_swap_total 150
telemt_pool_force_close_total 4602
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 44971
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3965
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42131
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40369
telemt_me_writer_teardown_success_total{mode="normal"} 46096
telemt_me_writer_teardown_noop_total 44979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91075
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.064541
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91075
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 1119
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6796664
telemt_user_connections_current{user="hello"} 4571
telemt_user_octets_from_client{user="hello"} 177872574243 (165.66 GB)
telemt_user_octets_to_client{user="hello"} 3128340881822 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1755
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 139843.0 (38h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8743828
telemt_connections_bad_total 728324
telemt_connections_current 3839
telemt_connections_me_current 3839
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 279281
telemt_upstream_connect_attempt_total 61713
telemt_upstream_connect_success_total 60998
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3726
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 3702471
telemt_me_route_drop_channel_closed_total 251
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6574152
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1023
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
telemt_me_writers_active_current 44
telemt_desync_total 30372
telemt_desync_full_logged_total 10316
telemt_desync_suppressed_total 20056
telemt_desync_frames_bucket_total{bucket="1_2"} 7416
telemt_desync_frames_bucket_total{bucket="3_10"} 11716
telemt_desync_frames_bucket_total{bucket="gt_10"} 11240
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 45675
telemt_me_writer_removed_unexpected_total 1456
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41153
telemt_me_writer_teardown_success_total{mode="normal"} 47069
telemt_me_writer_teardown_noop_total 45692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.955777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1360
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6565336
telemt_user_connections_current{user="hello"} 3839
telemt_user_octets_from_client{user="hello"} 161804003091 (150.69 GB)
telemt_user_octets_to_client{user="hello"} 2848079434019 (2.59 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1523
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 10119.9 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4302068
telemt_connections_bad_total 273992
telemt_connections_current 6121
telemt_connections_me_current 6121
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 66157
telemt_upstream_connect_attempt_total 23016
telemt_upstream_connect_success_total 21982
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 22813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_timeout_total 419
telemt_me_reconnect_attempts_total 2222
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 9842600
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3588119
telemt_me_endpoint_quarantine_total 77
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 86
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
telemt_desync_total 5210
telemt_desync_full_logged_total 1370
telemt_desync_suppressed_total 3840
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 2087
telemt_desync_frames_bucket_total{bucket="gt_10"} 2162
telemt_pool_swap_total 9
telemt_pool_force_close_total 399
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 2684
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2285
telemt_me_writer_teardown_success_total{mode="normal"} 2933
telemt_me_writer_teardown_noop_total 2687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.973194
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 214
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 3603475
telemt_user_connections_current{user="hello"} 6121
telemt_user_octets_from_client{user="hello"} 19551199250 (18.21 GB)
telemt_user_octets_to_client{user="hello"} 105587771295 (98.34 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2211
telemt_user_unique_ips_recent_window{user="hello"} 1934
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 139846.7 (38h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8478590
telemt_connections_bad_total 736317
telemt_connections_current 4175
telemt_connections_me_current 4175
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 176208
telemt_upstream_connect_attempt_total 86961
telemt_upstream_connect_success_total 86098
telemt_upstream_connect_fail_total 742
telemt_upstream_connect_attempts_per_request{bucket="1"} 86840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30789
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 742
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70704
telemt_me_reconnect_success_total 2203
telemt_me_reader_eof_total 1934
telemt_me_idle_close_by_peer_total 1933
telemt_me_route_drop_no_conn_total 3794903
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6694737
telemt_me_endpoint_quarantine_total 942
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1050
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
telemt_me_writers_active_current 44
telemt_desync_total 34171
telemt_desync_full_logged_total 11773
telemt_desync_suppressed_total 22398
telemt_desync_frames_bucket_total{bucket="1_2"} 7009
telemt_desync_frames_bucket_total{bucket="3_10"} 13115
telemt_desync_frames_bucket_total{bucket="gt_10"} 14047
telemt_pool_swap_total 145
telemt_pool_force_close_total 4223
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 48067
telemt_me_writer_removed_unexpected_total 1963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4956
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45099
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43844
telemt_me_writer_teardown_success_total{mode="normal"} 50055
telemt_me_writer_teardown_noop_total 48068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98123
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.820874
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98123
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1828
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6697757
telemt_user_connections_current{user="hello"} 4175
telemt_user_octets_from_client{user="hello"} 159726897907 (148.76 GB)
telemt_user_octets_to_client{user="hello"} 2629757450925 (2.39 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1541
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 76682.7 (21h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7709531
telemt_connections_bad_total 283188
telemt_connections_current 5020
telemt_connections_me_current 5020
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3199896
telemt_upstream_connect_attempt_total 39464
telemt_upstream_connect_success_total 39178
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47788
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_route_drop_no_conn_total 2472419
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3782631
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 583
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20610
telemt_desync_full_logged_total 6902
telemt_desync_suppressed_total 13708
telemt_desync_frames_bucket_total{bucket="1_2"} 4188
telemt_desync_frames_bucket_total{bucket="3_10"} 7976
telemt_desync_frames_bucket_total{bucket="gt_10"} 8446
telemt_pool_swap_total 81
telemt_pool_force_close_total 2459
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 27137
telemt_me_writer_removed_unexpected_total 1078
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25821
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 361
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24678
telemt_me_writer_teardown_success_total{mode="normal"} 28241
telemt_me_writer_teardown_noop_total 27144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55385
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.391585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55385
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3780950
telemt_user_connections_current{user="hello"} 5020
telemt_user_octets_from_client{user="hello"} 88112865884 (82.06 GB)
telemt_user_octets_to_client{user="hello"} 1520920922574 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2015
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57653.3 (16h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 612921
telemt_connections_bad_total 5525
telemt_connections_current 920
telemt_connections_me_current 920
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11894
telemt_upstream_connect_attempt_total 29982
telemt_upstream_connect_success_total 29913
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 203389
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553924
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_warm_current 20
telemt_desync_total 3018
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 2160
telemt_desync_frames_bucket_total{bucket="1_2"} 796
telemt_desync_frames_bucket_total{bucket="3_10"} 1184
telemt_desync_frames_bucket_total{bucket="gt_10"} 1038
telemt_pool_swap_total 60
telemt_pool_force_close_total 1464
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24414
telemt_me_writer_removed_unexpected_total 529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23134
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1388
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22950
telemt_me_writer_teardown_success_total{mode="normal"} 24961
telemt_me_writer_teardown_noop_total 24414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49375
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.674583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49375
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 492
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 555821
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 10621375085 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 260971423747 (243.05 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 139851.0 (38h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10276614
telemt_connections_bad_total 1198983
telemt_connections_current 5684
telemt_connections_me_current 5684
telemt_handshake_timeouts_total 271980
telemt_upstream_connect_attempt_total 53445
telemt_upstream_connect_success_total 53240
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_reconnect_attempts_total 2053
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1065
telemt_me_idle_close_by_peer_total 1065
telemt_me_route_drop_no_conn_total 2990876
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7676517
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
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
telemt_desync_total 31346
telemt_desync_full_logged_total 10304
telemt_desync_suppressed_total 21042
telemt_desync_frames_bucket_total{bucket="1_2"} 7587
telemt_desync_frames_bucket_total{bucket="3_10"} 11497
telemt_desync_frames_bucket_total{bucket="gt_10"} 12262
telemt_pool_swap_total 155
telemt_pool_force_close_total 4216
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 48202
telemt_me_writer_removed_unexpected_total 1023
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45352
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43986
telemt_me_writer_teardown_success_total{mode="normal"} 49258
telemt_me_writer_teardown_noop_total 48204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97462
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.663720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97462
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 960
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7648078
telemt_user_connections_current{user="hello"} 5684
telemt_user_octets_from_client{user="hello"} 148371057460 (138.18 GB)
telemt_user_octets_to_client{user="hello"} 3544720647760 (3.22 TB)
telemt_user_unique_ips_current{user="hello"} 2048
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 139847.7 (38h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8997014
telemt_connections_bad_total 1019578
telemt_connections_current 4530
telemt_connections_me_current 4530
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 229005
telemt_upstream_connect_attempt_total 77945
telemt_upstream_connect_success_total 77386
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 77874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1970
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_reconnect_attempts_total 6647
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1402
telemt_me_idle_close_by_peer_total 1402
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3465553
telemt_me_route_drop_channel_closed_total 276
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6890839
telemt_me_endpoint_quarantine_total 1088
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1061
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
telemt_me_writers_active_current 48
telemt_desync_total 30622
telemt_desync_full_logged_total 10061
telemt_desync_suppressed_total 20561
telemt_desync_frames_bucket_total{bucket="1_2"} 7575
telemt_desync_frames_bucket_total{bucket="3_10"} 11364
telemt_desync_frames_bucket_total{bucket="gt_10"} 11683
telemt_pool_swap_total 152
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 46851
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43768
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 311
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42700
telemt_me_writer_teardown_success_total{mode="normal"} 48336
telemt_me_writer_teardown_noop_total 46855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95191
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.922584
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95191
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6898568
telemt_user_connections_current{user="hello"} 4530
telemt_user_octets_from_client{user="hello"} 123630494385 (115.14 GB)
telemt_user_octets_to_client{user="hello"} 2838383347675 (2.58 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1713
telemt_user_unique_ips_recent_window{user="hello"} 731
```