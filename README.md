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

# Server Metrics 2026-03-22 14:16:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61810.9 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1979820
telemt_connections_bad_total 85004
telemt_connections_current 1682
telemt_connections_me_current 1682
telemt_handshake_timeouts_total 81359
telemt_upstream_connect_attempt_total 23094
telemt_upstream_connect_success_total 23093
telemt_upstream_connect_attempts_per_request{bucket="1"} 23093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15021
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 925
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 1444332
telemt_me_route_drop_channel_closed_total 638
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688574
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 46
telemt_desync_total 9090
telemt_desync_full_logged_total 2810
telemt_desync_suppressed_total 6280
telemt_desync_frames_bucket_total{bucket="1_2"} 2516
telemt_desync_frames_bucket_total{bucket="3_10"} 3417
telemt_desync_frames_bucket_total{bucket="gt_10"} 3157
telemt_pool_swap_total 68
telemt_pool_force_close_total 2056
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 21062
telemt_me_writer_removed_unexpected_total 373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19006
telemt_me_writer_teardown_success_total{mode="normal"} 21274
telemt_me_writer_teardown_noop_total 21066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.037855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 336
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1685562
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 26246261372 (24.44 GB)
telemt_user_octets_to_client{user="hello"} 487273374592 (453.81 GB)
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 75177.5 (20h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3179674
telemt_connections_bad_total 292840
telemt_connections_current 3087
telemt_connections_me_current 3087
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 75798
telemt_upstream_connect_attempt_total 48257
telemt_upstream_connect_success_total 47677
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 48191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5278
telemt_me_reconnect_success_total 1813
telemt_me_reader_eof_total 1737
telemt_me_idle_close_by_peer_total 1737
telemt_me_route_drop_no_conn_total 2979904
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2507765
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 585
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
telemt_me_writers_active_current 129
telemt_desync_total 9925
telemt_desync_full_logged_total 5533
telemt_desync_suppressed_total 4392
telemt_desync_frames_bucket_total{bucket="1_2"} 2343
telemt_desync_frames_bucket_total{bucket="3_10"} 3907
telemt_desync_frames_bucket_total{bucket="gt_10"} 3675
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 29771
telemt_me_writer_removed_unexpected_total 1695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3409
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28058
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27701
telemt_me_writer_teardown_success_total{mode="normal"} 31467
telemt_me_writer_teardown_noop_total 29771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.019808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1534
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 2519325
telemt_user_connections_current{user="hello"} 3087
telemt_user_octets_from_client{user="hello"} 30325145167 (28.24 GB)
telemt_user_octets_to_client{user="hello"} 578541352654 (538.81 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1731
telemt_user_unique_ips_recent_window{user="hello"} 686
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 150037.2 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14255799
telemt_connections_bad_total 1258692
telemt_connections_current 4785
telemt_connections_me_current 4785
telemt_handshake_timeouts_total 357318
telemt_upstream_connect_attempt_total 54318
telemt_upstream_connect_success_total 54236
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 54244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2466
telemt_me_reconnect_success_total 1290
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1233
telemt_me_route_drop_no_conn_total 12588278
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11435523
telemt_me_endpoint_quarantine_total 952
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1116
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
telemt_desync_total 46570
telemt_desync_full_logged_total 14708
telemt_desync_suppressed_total 31862
telemt_desync_frames_bucket_total{bucket="1_2"} 10542
telemt_desync_frames_bucket_total{bucket="3_10"} 18233
telemt_desync_frames_bucket_total{bucket="gt_10"} 17795
telemt_pool_swap_total 161
telemt_pool_force_close_total 5506
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 886
telemt_me_draining_writers_reap_progress_total 49537
telemt_me_writer_removed_unexpected_total 1189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5066
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44031
telemt_me_writer_teardown_success_total{mode="normal"} 50053
telemt_me_writer_teardown_noop_total 49586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99639
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 257.606887
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99639
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 886
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1112
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11423015
telemt_user_connections_current{user="hello"} 4785
telemt_user_octets_from_client{user="hello"} 163040623000 (151.84 GB)
telemt_user_octets_to_client{user="hello"} 3017263916520 (2.74 TB)
telemt_user_unique_ips_current{user="hello"} 1854
telemt_user_unique_ips_recent_window{user="hello"} 835
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 150038.6 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10519369
telemt_connections_bad_total 1003287
telemt_connections_current 4711
telemt_connections_me_current 4711
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 313592
telemt_upstream_connect_attempt_total 80708
telemt_upstream_connect_success_total 79564
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 80386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31980
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3705
telemt_me_reconnect_success_total 1476
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 4178537
telemt_me_route_drop_channel_closed_total 457
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7852567
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1137
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
telemt_desync_total 34994
telemt_desync_full_logged_total 11777
telemt_desync_suppressed_total 23217
telemt_desync_frames_bucket_total{bucket="1_2"} 8635
telemt_desync_frames_bucket_total{bucket="3_10"} 13465
telemt_desync_frames_bucket_total{bucket="gt_10"} 12894
telemt_pool_swap_total 160
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 47746
telemt_me_writer_removed_unexpected_total 1383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4514
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 428
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42804
telemt_me_writer_teardown_success_total{mode="normal"} 48986
telemt_me_writer_teardown_noop_total 47761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96747
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.144920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96747
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7791886
telemt_user_connections_current{user="hello"} 4711
telemt_user_octets_from_client{user="hello"} 196864127133 (183.34 GB)
telemt_user_octets_to_client{user="hello"} 3510630559986 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1902
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 150002.7 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9970782
telemt_connections_bad_total 844654
telemt_connections_current 4498
telemt_connections_me_current 4498
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 321594
telemt_upstream_connect_attempt_total 66134
telemt_upstream_connect_success_total 65228
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 65409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2015
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4529
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1592
telemt_me_idle_close_by_peer_total 1591
telemt_me_route_drop_no_conn_total 4908495
telemt_me_route_drop_channel_closed_total 334
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7529253
telemt_me_endpoint_quarantine_total 1036
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1100
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 34915
telemt_desync_full_logged_total 11565
telemt_desync_suppressed_total 23350
telemt_desync_frames_bucket_total{bucket="1_2"} 8827
telemt_desync_frames_bucket_total{bucket="3_10"} 13361
telemt_desync_frames_bucket_total{bucket="gt_10"} 12727
telemt_pool_swap_total 156
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 48378
telemt_me_writer_removed_unexpected_total 1737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43493
telemt_me_writer_teardown_success_total{mode="normal"} 50028
telemt_me_writer_teardown_noop_total 48445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3163.831423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7522938
telemt_user_connections_current{user="hello"} 4497
telemt_user_octets_from_client{user="hello"} 175885501865 (163.81 GB)
telemt_user_octets_to_client{user="hello"} 3139269978005 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1849
telemt_user_unique_ips_recent_window{user="hello"} 688
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 20297.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8578585
telemt_connections_bad_total 541109
telemt_connections_current 7091
telemt_connections_me_current 7091
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 138938
telemt_upstream_connect_attempt_total 28790
telemt_upstream_connect_success_total 27367
telemt_upstream_connect_fail_total 1030
telemt_upstream_connect_attempts_per_request{bucket="1"} 28397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4743
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1030
telemt_me_keepalive_timeout_total 789
telemt_me_reconnect_attempts_total 5511
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 21044924
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7134985
telemt_me_endpoint_quarantine_total 127
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 158
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
telemt_me_writers_active_current 101
telemt_desync_total 10552
telemt_desync_full_logged_total 2723
telemt_desync_suppressed_total 7829
telemt_desync_frames_bucket_total{bucket="1_2"} 1847
telemt_desync_frames_bucket_total{bucket="3_10"} 4262
telemt_desync_frames_bucket_total{bucket="gt_10"} 4443
telemt_pool_swap_total 18
telemt_pool_force_close_total 745
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 271
telemt_me_draining_writers_reap_progress_total 5302
telemt_me_writer_removed_unexpected_total 504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4825
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4557
telemt_me_writer_teardown_success_total{mode="normal"} 5765
telemt_me_writer_teardown_noop_total 5305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.315401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 271
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7149900
telemt_user_connections_current{user="hello"} 7091
telemt_user_octets_from_client{user="hello"} 41366163351 (38.53 GB)
telemt_user_octets_to_client{user="hello"} 209321982720 (194.95 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2588
telemt_user_unique_ips_recent_window{user="hello"} 1419
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 150009.0 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9697193
telemt_connections_bad_total 802000
telemt_connections_current 5407
telemt_connections_me_current 5407
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 209924
telemt_upstream_connect_attempt_total 90551
telemt_upstream_connect_success_total 89638
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 90429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71398
telemt_me_reconnect_success_total 2466
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2196
telemt_me_route_drop_no_conn_total 4781724
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7656676
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1118
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 39359
telemt_desync_full_logged_total 13460
telemt_desync_suppressed_total 25899
telemt_desync_frames_bucket_total{bucket="1_2"} 7996
telemt_desync_frames_bucket_total{bucket="3_10"} 15272
telemt_desync_frames_bucket_total{bucket="gt_10"} 16091
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 555
telemt_me_draining_writers_reap_progress_total 51062
telemt_me_writer_removed_unexpected_total 2224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46530
telemt_me_writer_teardown_success_total{mode="normal"} 53303
telemt_me_writer_teardown_noop_total 51063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.836248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 555
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2074
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7657725
telemt_user_connections_current{user="hello"} 5407
telemt_user_octets_from_client{user="hello"} 175597010271 (163.54 GB)
telemt_user_octets_to_client{user="hello"} 2897460596817 (2.64 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2207
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 86845.0 (24h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9780669
telemt_connections_bad_total 356300
telemt_connections_current 4256
telemt_connections_me_current 4256
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4105931
telemt_upstream_connect_attempt_total 42711
telemt_upstream_connect_success_total 42401
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 42704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47938
telemt_me_reconnect_success_total 1451
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3590555
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4715030
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 25766
telemt_desync_full_logged_total 8668
telemt_desync_suppressed_total 17098
telemt_desync_frames_bucket_total{bucket="1_2"} 5201
telemt_desync_frames_bucket_total{bucket="3_10"} 10210
telemt_desync_frames_bucket_total{bucket="gt_10"} 10355
telemt_pool_swap_total 91
telemt_pool_force_close_total 2830
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 291
telemt_me_draining_writers_reap_progress_total 30025
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2421
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27195
telemt_me_writer_teardown_success_total{mode="normal"} 31239
telemt_me_writer_teardown_noop_total 30032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61271
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.211474
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61271
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 291
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4709355
telemt_user_connections_current{user="hello"} 4256
telemt_user_octets_from_client{user="hello"} 102368854424 (95.34 GB)
telemt_user_octets_to_client{user="hello"} 1788433086190 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1683
telemt_user_unique_ips_recent_window{user="hello"} 790
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67815.8 (18h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 823850
telemt_connections_bad_total 10704
telemt_connections_current 1075
telemt_connections_me_current 1075
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15371
telemt_upstream_connect_attempt_total 34229
telemt_upstream_connect_success_total 34144
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 453
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1561
telemt_me_reconnect_success_total 664
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_route_drop_no_conn_total 283305
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735652
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 565
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
telemt_me_writers_active_current 44
telemt_desync_total 4046
telemt_desync_full_logged_total 1226
telemt_desync_suppressed_total 2820
telemt_desync_frames_bucket_total{bucket="1_2"} 983
telemt_desync_frames_bucket_total{bucket="3_10"} 1610
telemt_desync_frames_bucket_total{bucket="gt_10"} 1453
telemt_pool_swap_total 72
telemt_pool_force_close_total 1798
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 28144
telemt_me_writer_removed_unexpected_total 618
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26617
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26346
telemt_me_writer_teardown_success_total{mode="normal"} 28785
telemt_me_writer_teardown_noop_total 28146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56931
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.132706
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56931
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 567
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 736849
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 13670628889 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 345024653619 (321.33 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 150014.5 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11835118
telemt_connections_bad_total 1380833
telemt_connections_current 6389
telemt_connections_me_current 6389
telemt_handshake_timeouts_total 323462
telemt_upstream_connect_attempt_total 56411
telemt_upstream_connect_success_total 56188
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 56360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 2202
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1142
telemt_me_route_drop_no_conn_total 3812150
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8912849
telemt_me_endpoint_quarantine_total 1025
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1123
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
telemt_desync_total 36675
telemt_desync_full_logged_total 11985
telemt_desync_suppressed_total 24690
telemt_desync_frames_bucket_total{bucket="1_2"} 8756
telemt_desync_frames_bucket_total{bucket="3_10"} 13585
telemt_desync_frames_bucket_total{bucket="gt_10"} 14334
telemt_pool_swap_total 166
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 50816
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4178
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47765
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4418
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46234
telemt_me_writer_teardown_success_total{mode="normal"} 51943
telemt_me_writer_teardown_noop_total 50818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.103196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8882880
telemt_user_connections_current{user="hello"} 6389
telemt_user_octets_from_client{user="hello"} 170973384904 (159.23 GB)
telemt_user_octets_to_client{user="hello"} 3977779928128 (3.62 TB)
telemt_user_unique_ips_current{user="hello"} 2320
telemt_user_unique_ips_recent_window{user="hello"} 836
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 150010.0 (41h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10232133
telemt_connections_bad_total 1146316
telemt_connections_current 5152
telemt_connections_me_current 5152
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 266722
telemt_upstream_connect_attempt_total 81994
telemt_upstream_connect_success_total 81390
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 81913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 8674
telemt_me_reconnect_success_total 1958
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1825
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4756805
telemt_me_route_drop_channel_closed_total 326
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7888756
telemt_me_endpoint_quarantine_total 1143
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1127
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 42
telemt_desync_total 35972
telemt_desync_full_logged_total 11663
telemt_desync_suppressed_total 24309
telemt_desync_frames_bucket_total{bucket="1_2"} 8889
telemt_desync_frames_bucket_total{bucket="3_10"} 13417
telemt_desync_frames_bucket_total{bucket="gt_10"} 13666
telemt_pool_swap_total 159
telemt_pool_force_close_total 4442
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 574
telemt_me_draining_writers_reap_progress_total 50129
telemt_me_writer_removed_unexpected_total 1850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5199
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45687
telemt_me_writer_teardown_success_total{mode="normal"} 52046
telemt_me_writer_teardown_noop_total 50133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.689660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 574
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 7895465
telemt_user_connections_current{user="hello"} 5152
telemt_user_octets_from_client{user="hello"} 138684422225 (129.16 GB)
telemt_user_octets_to_client{user="hello"} 3075759396147 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1956
telemt_user_unique_ips_recent_window{user="hello"} 733
```