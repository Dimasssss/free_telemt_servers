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

# Server Metrics 2026-03-22 13:20:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58413.0 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1809046
telemt_connections_bad_total 81056
telemt_connections_current 1580
telemt_connections_me_current 1580
telemt_handshake_timeouts_total 77958
telemt_upstream_connect_attempt_total 21952
telemt_upstream_connect_success_total 21951
telemt_upstream_connect_attempts_per_request{bucket="1"} 21951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 901
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 360
telemt_me_idle_close_by_peer_total 360
telemt_me_route_drop_no_conn_total 1272608
telemt_me_route_drop_channel_closed_total 570
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536723
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 404
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 462
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8655
telemt_desync_full_logged_total 2641
telemt_desync_suppressed_total 6014
telemt_desync_frames_bucket_total{bucket="1_2"} 2424
telemt_desync_frames_bucket_total{bucket="3_10"} 3261
telemt_desync_frames_bucket_total{bucket="gt_10"} 2970
telemt_pool_swap_total 64
telemt_pool_force_close_total 1920
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 20017
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18807
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18097
telemt_me_writer_teardown_success_total{mode="normal"} 20230
telemt_me_writer_teardown_noop_total 20021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 150.556342
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1533847
telemt_user_connections_current{user="hello"} 1580
telemt_user_octets_from_client{user="hello"} 24052654888 (22.40 GB)
telemt_user_octets_to_client{user="hello"} 448459960428 (417.66 GB)
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 71779.5 (19h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2968087
telemt_connections_bad_total 280102
telemt_connections_current 1948
telemt_connections_me_current 1948
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 69260
telemt_upstream_connect_attempt_total 46455
telemt_upstream_connect_success_total 45909
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 46391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3622
telemt_me_reconnect_success_total 1612
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1487
telemt_me_route_drop_no_conn_total 2765495
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2330682
telemt_me_endpoint_quarantine_total 602
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 561
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
telemt_desync_total 9086
telemt_desync_full_logged_total 5081
telemt_desync_suppressed_total 4005
telemt_desync_frames_bucket_total{bucket="1_2"} 2129
telemt_desync_frames_bucket_total{bucket="3_10"} 3552
telemt_desync_frames_bucket_total{bucket="gt_10"} 3405
telemt_pool_swap_total 71
telemt_pool_force_close_total 2036
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 28425
telemt_me_writer_removed_unexpected_total 1446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26761
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1792
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26389
telemt_me_writer_teardown_success_total{mode="normal"} 29872
telemt_me_writer_teardown_noop_total 28425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.425020
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2342291
telemt_user_connections_current{user="hello"} 1948
telemt_user_octets_from_client{user="hello"} 28405148595 (26.45 GB)
telemt_user_octets_to_client{user="hello"} 540177398062 (503.08 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 146639.3 (40h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13615575
telemt_connections_bad_total 1196005
telemt_connections_current 5922
telemt_connections_me_current 5922
telemt_handshake_timeouts_total 344706
telemt_upstream_connect_attempt_total 53293
telemt_upstream_connect_success_total 53211
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2431
telemt_me_reconnect_success_total 1274
telemt_me_reader_eof_total 1216
telemt_me_idle_close_by_peer_total 1215
telemt_me_route_drop_no_conn_total 11727809
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10913031
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1090
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
telemt_desync_total 44464
telemt_desync_full_logged_total 14142
telemt_desync_suppressed_total 30322
telemt_desync_frames_bucket_total{bucket="1_2"} 10045
telemt_desync_frames_bucket_total{bucket="3_10"} 17371
telemt_desync_frames_bucket_total{bucket="gt_10"} 17048
telemt_pool_swap_total 157
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 851
telemt_me_draining_writers_reap_progress_total 48604
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 430
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43228
telemt_me_writer_teardown_success_total{mode="normal"} 49111
telemt_me_writer_teardown_noop_total 48652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 244.158088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 851
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1097
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 10901134
telemt_user_connections_current{user="hello"} 5922
telemt_user_octets_from_client{user="hello"} 157798688200 (146.96 GB)
telemt_user_octets_to_client{user="hello"} 2928607148532 (2.66 TB)
telemt_user_unique_ips_current{user="hello"} 2347
telemt_user_unique_ips_recent_window{user="hello"} 953
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 146640.8 (40h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10122188
telemt_connections_bad_total 943068
telemt_connections_current 5342
telemt_connections_me_current 5342
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 303467
telemt_upstream_connect_attempt_total 79675
telemt_upstream_connect_success_total 78538
telemt_upstream_connect_fail_total 816
telemt_upstream_connect_attempts_per_request{bucket="1"} 79354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 816
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3625
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1323
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 4049296
telemt_me_route_drop_channel_closed_total 423
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7555279
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1111
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 33910
telemt_desync_full_logged_total 11427
telemt_desync_suppressed_total 22483
telemt_desync_frames_bucket_total{bucket="1_2"} 8351
telemt_desync_frames_bucket_total{bucket="3_10"} 13045
telemt_desync_frames_bucket_total{bucket="gt_10"} 12514
telemt_pool_swap_total 156
telemt_pool_force_close_total 4796
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 46825
telemt_me_writer_removed_unexpected_total 1355
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43819
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42029
telemt_me_writer_teardown_success_total{mode="normal"} 48048
telemt_me_writer_teardown_noop_total 46840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94888
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.939620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94888
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 1229
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7495247
telemt_user_connections_current{user="hello"} 5342
telemt_user_octets_from_client{user="hello"} 192029028593 (178.84 GB)
telemt_user_octets_to_client{user="hello"} 3388643336658 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2265
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 146644.7 (40h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9604872
telemt_connections_bad_total 801105
telemt_connections_current 4742
telemt_connections_me_current 4742
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 311312
telemt_upstream_connect_attempt_total 65081
telemt_upstream_connect_success_total 64180
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 3993
telemt_me_reconnect_success_total 1773
telemt_me_reader_eof_total 1547
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 4554442
telemt_me_route_drop_channel_closed_total 321
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7244466
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1073
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 80
telemt_desync_total 33602
telemt_desync_full_logged_total 11164
telemt_desync_suppressed_total 22438
telemt_desync_frames_bucket_total{bucket="1_2"} 8547
telemt_desync_frames_bucket_total{bucket="3_10"} 12875
telemt_desync_frames_bucket_total{bucket="gt_10"} 12180
telemt_pool_swap_total 152
telemt_pool_force_close_total 4730
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 47407
telemt_me_writer_removed_unexpected_total 1694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44302
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42677
telemt_me_writer_teardown_success_total{mode="normal"} 49023
telemt_me_writer_teardown_noop_total 47474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3152.793977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 7238751
telemt_user_connections_current{user="hello"} 4742
telemt_user_octets_from_client{user="hello"} 170536136673 (158.82 GB)
telemt_user_octets_to_client{user="hello"} 3026969797109 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1355
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 16884.8 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7107942
telemt_connections_bad_total 459070
telemt_connections_current 6486
telemt_connections_me_current 6486
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 111664
telemt_upstream_connect_attempt_total 27634
telemt_upstream_connect_success_total 26295
telemt_upstream_connect_fail_total 1009
telemt_upstream_connect_attempts_per_request{bucket="1"} 27304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1009
telemt_me_keepalive_timeout_total 629
telemt_me_reconnect_attempts_total 2594
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 17049860
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5908489
telemt_me_endpoint_quarantine_total 107
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 136
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
telemt_me_writers_active_current 44
telemt_desync_total 8684
telemt_desync_full_logged_total 2231
telemt_desync_suppressed_total 6453
telemt_desync_frames_bucket_total{bucket="1_2"} 1568
telemt_desync_frames_bucket_total{bucket="3_10"} 3519
telemt_desync_frames_bucket_total{bucket="gt_10"} 3597
telemt_pool_swap_total 15
telemt_pool_force_close_total 624
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 4464
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4054
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 180
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3840
telemt_me_writer_teardown_success_total{mode="normal"} 4845
telemt_me_writer_teardown_noop_total 4467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9312
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.808839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9312
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 312
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 5923797
telemt_user_connections_current{user="hello"} 6486
telemt_user_octets_from_client{user="hello"} 31958990415 (29.76 GB)
telemt_user_octets_to_client{user="hello"} 176450906176 (164.33 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2445
telemt_user_unique_ips_recent_window{user="hello"} 1275
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 146611.5 (40h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9304475
telemt_connections_bad_total 775645
telemt_connections_current 5155
telemt_connections_me_current 5155
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 200934
telemt_upstream_connect_attempt_total 89436
telemt_upstream_connect_success_total 88539
telemt_upstream_connect_fail_total 775
telemt_upstream_connect_attempts_per_request{bucket="1"} 89314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 775
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71236
telemt_me_reconnect_success_total 2399
telemt_me_reader_eof_total 2129
telemt_me_idle_close_by_peer_total 2128
telemt_me_route_drop_no_conn_total 4522217
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7349210
telemt_me_endpoint_quarantine_total 978
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1095
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 37611
telemt_desync_full_logged_total 12861
telemt_desync_suppressed_total 24750
telemt_desync_frames_bucket_total{bucket="1_2"} 7637
telemt_desync_frames_bucket_total{bucket="3_10"} 14542
telemt_desync_frames_bucket_total{bucket="gt_10"} 15432
telemt_pool_swap_total 150
telemt_pool_force_close_total 4428
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 50122
telemt_me_writer_removed_unexpected_total 2157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5289
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3823
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 605
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45694
telemt_me_writer_teardown_success_total{mode="normal"} 52295
telemt_me_writer_teardown_noop_total 50123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102418
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.399473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102418
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 4248
telemt_me_writer_restored_same_endpoint_total 2013
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 7350833
telemt_user_connections_current{user="hello"} 5155
telemt_user_octets_from_client{user="hello"} 170540053863 (158.83 GB)
telemt_user_octets_to_client{user="hello"} 2806893289261 (2.55 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2025
telemt_user_unique_ips_recent_window{user="hello"} 673
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 83447.6 (23h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9140647
telemt_connections_bad_total 322133
telemt_connections_current 4772
telemt_connections_me_current 4772
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3849428
telemt_upstream_connect_attempt_total 41657
telemt_upstream_connect_success_total 41357
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 41650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_reconnect_attempts_total 47899
telemt_me_reconnect_success_total 1430
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 3319531
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4410733
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 627
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 24125
telemt_desync_full_logged_total 8088
telemt_desync_suppressed_total 16037
telemt_desync_frames_bucket_total{bucket="1_2"} 4890
telemt_desync_frames_bucket_total{bucket="3_10"} 9490
telemt_desync_frames_bucket_total{bucket="gt_10"} 9745
telemt_pool_swap_total 87
telemt_pool_force_close_total 2703
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 29093
telemt_me_writer_removed_unexpected_total 1162
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2639
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27644
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 402
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26390
telemt_me_writer_teardown_success_total{mode="normal"} 30283
telemt_me_writer_teardown_noop_total 29100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.850269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4405728
telemt_user_connections_current{user="hello"} 4772
telemt_user_octets_from_client{user="hello"} 97668939704 (90.96 GB)
telemt_user_octets_to_client{user="hello"} 1697506860822 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1836
telemt_user_unique_ips_recent_window{user="hello"} 691
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64419.3 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746396
telemt_connections_bad_total 8620
telemt_connections_current 1177
telemt_connections_me_current 1177
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14172
telemt_upstream_connect_attempt_total 32831
telemt_upstream_connect_success_total 32747
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 398
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1459
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 251098
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671884
telemt_me_endpoint_quarantine_total 579
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 539
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_active_current 44
telemt_desync_total 3711
telemt_desync_full_logged_total 1096
telemt_desync_suppressed_total 2615
telemt_desync_frames_bucket_total{bucket="1_2"} 899
telemt_desync_frames_bucket_total{bucket="3_10"} 1470
telemt_desync_frames_bucket_total{bucket="gt_10"} 1342
telemt_pool_swap_total 68
telemt_pool_force_close_total 1680
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 26925
telemt_me_writer_removed_unexpected_total 589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2063
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25245
telemt_me_writer_teardown_success_total{mode="normal"} 27536
telemt_me_writer_teardown_noop_total 26927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.000671
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 544
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 673484
telemt_user_connections_current{user="hello"} 1177
telemt_user_octets_from_client{user="hello"} 12722781621 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 320849049839 (298.81 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 146616.0 (40h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11359082
telemt_connections_bad_total 1330990
telemt_connections_current 5733
telemt_connections_me_current 5733
telemt_handshake_timeouts_total 306049
telemt_upstream_connect_attempt_total 55428
telemt_upstream_connect_success_total 55213
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2179
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3588813
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8528777
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1100
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
telemt_me_writers_active_current 46
telemt_desync_total 34904
telemt_desync_full_logged_total 11457
telemt_desync_suppressed_total 23447
telemt_desync_frames_bucket_total{bucket="1_2"} 8335
telemt_desync_frames_bucket_total{bucket="3_10"} 12928
telemt_desync_frames_bucket_total{bucket="gt_10"} 13641
telemt_pool_swap_total 162
telemt_pool_force_close_total 4444
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 561
telemt_me_draining_writers_reap_progress_total 49936
telemt_me_writer_removed_unexpected_total 1076
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4088
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46960
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45492
telemt_me_writer_teardown_success_total{mode="normal"} 51048
telemt_me_writer_teardown_noop_total 49938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.117201
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 561
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8499532
telemt_user_connections_current{user="hello"} 5733
telemt_user_octets_from_client{user="hello"} 164090665904 (152.82 GB)
telemt_user_octets_to_client{user="hello"} 3832578074424 (3.49 TB)
telemt_user_unique_ips_current{user="hello"} 2155
telemt_user_unique_ips_recent_window{user="hello"} 767
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 146612.9 (40h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9809374
telemt_connections_bad_total 1100039
telemt_connections_current 4482
telemt_connections_me_current 4482
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 255741
telemt_upstream_connect_attempt_total 80908
telemt_upstream_connect_success_total 80318
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 80828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2004
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_reconnect_attempts_total 8547
telemt_me_reconnect_success_total 1918
telemt_me_reader_eof_total 1790
telemt_me_idle_close_by_peer_total 1790
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4371176
telemt_me_route_drop_channel_closed_total 313
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7547106
telemt_me_endpoint_quarantine_total 1115
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1103
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_active_current 89
telemt_desync_total 34086
telemt_desync_full_logged_total 11116
telemt_desync_suppressed_total 22970
telemt_desync_frames_bucket_total{bucket="1_2"} 8433
telemt_desync_frames_bucket_total{bucket="3_10"} 12701
telemt_desync_frames_bucket_total{bucket="gt_10"} 12952
telemt_pool_swap_total 155
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 49139
telemt_me_writer_removed_unexpected_total 1815
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45936
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3921
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44855
telemt_me_writer_teardown_success_total{mode="normal"} 51020
telemt_me_writer_teardown_noop_total 49143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.909034
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1561
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 7554452
telemt_user_connections_current{user="hello"} 4482
telemt_user_octets_from_client{user="hello"} 133657300937 (124.48 GB)
telemt_user_octets_to_client{user="hello"} 2989370057867 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1933
telemt_user_unique_ips_recent_window{user="hello"} 565
```