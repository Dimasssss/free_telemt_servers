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

# Server Metrics 2026-03-22 17:20:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72844.9 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2629394
telemt_connections_bad_total 142062
telemt_connections_current 1486
telemt_connections_me_current 1486
telemt_handshake_timeouts_total 90882
telemt_upstream_connect_attempt_total 26821
telemt_upstream_connect_success_total 26820
telemt_upstream_connect_attempts_per_request{bucket="1"} 26820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1088
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 464
telemt_me_idle_close_by_peer_total 464
telemt_me_route_drop_no_conn_total 2193225
telemt_me_route_drop_channel_closed_total 892
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2243856
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 496
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 10436
telemt_desync_full_logged_total 3303
telemt_desync_suppressed_total 7133
telemt_desync_frames_bucket_total{bucket="1_2"} 2790
telemt_desync_frames_bucket_total{bucket="3_10"} 3889
telemt_desync_frames_bucket_total{bucket="gt_10"} 3757
telemt_pool_swap_total 80
telemt_pool_force_close_total 2488
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 24497
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22933
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22009
telemt_me_writer_teardown_success_total{mode="normal"} 24718
telemt_me_writer_teardown_noop_total 24503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49221
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 238.850581
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49221
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 409
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2240171
telemt_user_connections_current{user="hello"} 1481
telemt_user_octets_from_client{user="hello"} 33089699440 (30.82 GB)
telemt_user_octets_to_client{user="hello"} 589970502496 (549.45 GB)
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 86211.5 (23h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3663267
telemt_connections_bad_total 332509
telemt_connections_current 1138
telemt_connections_me_current 1138
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 91715
telemt_upstream_connect_attempt_total 53556
telemt_upstream_connect_success_total 52888
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 53476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6213
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2185
telemt_me_idle_close_by_peer_total 2185
telemt_me_route_drop_no_conn_total 3550229
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2905439
telemt_me_endpoint_quarantine_total 687
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 666
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 11416
telemt_desync_full_logged_total 6378
telemt_desync_suppressed_total 5038
telemt_desync_frames_bucket_total{bucket="1_2"} 2662
telemt_desync_frames_bucket_total{bucket="3_10"} 4474
telemt_desync_frames_bucket_total{bucket="gt_10"} 4280
telemt_pool_swap_total 81
telemt_pool_force_close_total 2430
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 34297
telemt_me_writer_removed_unexpected_total 2138
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32333
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31867
telemt_me_writer_teardown_success_total{mode="normal"} 36443
telemt_me_writer_teardown_noop_total 34297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.155065
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1948
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 2916648
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 36794078463 (34.27 GB)
telemt_user_octets_to_client{user="hello"} 661268585478 (615.85 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 161071.2 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15505431
telemt_connections_bad_total 1473648
telemt_connections_current 2710
telemt_connections_me_current 2710
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 379097
telemt_upstream_connect_attempt_total 72436
telemt_upstream_connect_success_total 72339
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1677
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2698
telemt_me_reconnect_success_total 1387
telemt_me_reader_eof_total 1325
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 13851432
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12367580
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1198
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
telemt_me_writers_active_current 45
telemt_desync_total 50561
telemt_desync_full_logged_total 15883
telemt_desync_suppressed_total 34678
telemt_desync_frames_bucket_total{bucket="1_2"} 11295
telemt_desync_frames_bucket_total{bucket="3_10"} 19743
telemt_desync_frames_bucket_total{bucket="gt_10"} 19523
telemt_pool_swap_total 173
telemt_pool_force_close_total 5877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 950
telemt_me_draining_writers_reap_progress_total 52926
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4633
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48863
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5417
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47049
telemt_me_writer_teardown_success_total{mode="normal"} 53496
telemt_me_writer_teardown_noop_total 52976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 303.608011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 950
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1192
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12368613
telemt_user_connections_current{user="hello"} 2710
telemt_user_octets_from_client{user="hello"} 177717896645 (165.51 GB)
telemt_user_octets_to_client{user="hello"} 3214391465031 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 161072.8 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11181963
telemt_connections_bad_total 1088598
telemt_connections_current 1591
telemt_connections_me_current 1591
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 334607
telemt_upstream_connect_attempt_total 84626
telemt_upstream_connect_success_total 83468
telemt_upstream_connect_fail_total 834
telemt_upstream_connect_attempts_per_request{bucket="1"} 84302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 834
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3960
telemt_me_reconnect_success_total 1623
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1495
telemt_me_route_drop_no_conn_total 4390555
telemt_me_route_drop_channel_closed_total 483
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8334932
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1217
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
telemt_me_writers_active_current 44
telemt_desync_total 37056
telemt_desync_full_logged_total 12460
telemt_desync_suppressed_total 24596
telemt_desync_frames_bucket_total{bucket="1_2"} 9099
telemt_desync_frames_bucket_total{bucket="3_10"} 14285
telemt_desync_frames_bucket_total{bucket="gt_10"} 13672
telemt_pool_swap_total 171
telemt_pool_force_close_total 5320
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 51237
telemt_me_writer_removed_unexpected_total 1523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4711
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47891
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 478
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45917
telemt_me_writer_teardown_success_total{mode="normal"} 52602
telemt_me_writer_teardown_noop_total 51260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.757705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1384
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8273511
telemt_user_connections_current{user="hello"} 1591
telemt_user_octets_from_client{user="hello"} 206940652197 (192.73 GB)
telemt_user_octets_to_client{user="hello"} 3730475335602 (3.39 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 161036.8 (44h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10552570
telemt_connections_bad_total 910097
telemt_connections_current 1253
telemt_connections_me_current 1253
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 337550
telemt_upstream_connect_attempt_total 69942
telemt_upstream_connect_success_total 68953
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2090
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4760
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1674
telemt_me_idle_close_by_peer_total 1673
telemt_me_route_drop_no_conn_total 5162901
telemt_me_route_drop_channel_closed_total 367
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7961936
telemt_me_endpoint_quarantine_total 1096
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1184
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36600
telemt_desync_full_logged_total 12102
telemt_desync_suppressed_total 24498
telemt_desync_frames_bucket_total{bucket="1_2"} 9273
telemt_desync_frames_bucket_total{bucket="3_10"} 13996
telemt_desync_frames_bucket_total{bucket="gt_10"} 13331
telemt_pool_swap_total 168
telemt_pool_force_close_total 5242
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 51639
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5171
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46397
telemt_me_writer_teardown_success_total{mode="normal"} 53368
telemt_me_writer_teardown_noop_total 51710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3171.857586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 150
telemt_me_writer_restored_same_endpoint_total 1662
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 7954783
telemt_user_connections_current{user="hello"} 1253
telemt_user_octets_from_client{user="hello"} 183728470097 (171.11 GB)
telemt_user_octets_to_client{user="hello"} 3309414605565 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 31316.6 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10333718
telemt_connections_bad_total 629981
telemt_connections_current 2215
telemt_connections_me_current 2215
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 199239
telemt_upstream_connect_attempt_total 40960
telemt_upstream_connect_success_total 38883
telemt_upstream_connect_fail_total 1478
telemt_upstream_connect_attempts_per_request{bucket="1"} 40361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5915
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1478
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6121
telemt_me_reconnect_success_total 781
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 25008284
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8594380
telemt_me_endpoint_quarantine_total 194
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 246
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13581
telemt_desync_full_logged_total 3527
telemt_desync_suppressed_total 10054
telemt_desync_frames_bucket_total{bucket="1_2"} 2484
telemt_desync_frames_bucket_total{bucket="3_10"} 5512
telemt_desync_frames_bucket_total{bucket="gt_10"} 5585
telemt_pool_swap_total 30
telemt_pool_force_close_total 1160
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 377
telemt_me_draining_writers_reap_progress_total 8717
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1400
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7963
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7557
telemt_me_writer_teardown_success_total{mode="normal"} 9363
telemt_me_writer_teardown_noop_total 8722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.847991
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 377
telemt_me_refill_failed_total 295
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8616128
telemt_user_connections_current{user="hello"} 2215
telemt_user_octets_from_client{user="hello"} 69539490179 (64.76 GB)
telemt_user_octets_to_client{user="hello"} 350310659425 (326.25 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 161042.7 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10363299
telemt_connections_bad_total 871962
telemt_connections_current 1863
telemt_connections_me_current 1863
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 229619
telemt_upstream_connect_attempt_total 98689
telemt_upstream_connect_success_total 97666
telemt_upstream_connect_fail_total 869
telemt_upstream_connect_attempts_per_request{bucket="1"} 98535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 869
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72084
telemt_me_reconnect_success_total 2659
telemt_me_reader_eof_total 2360
telemt_me_idle_close_by_peer_total 2358
telemt_me_route_drop_no_conn_total 5097133
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8175030
telemt_me_endpoint_quarantine_total 1084
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1199
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 42857
telemt_desync_full_logged_total 14605
telemt_desync_suppressed_total 28252
telemt_desync_frames_bucket_total{bucket="1_2"} 8717
telemt_desync_frames_bucket_total{bucket="3_10"} 16547
telemt_desync_frames_bucket_total{bucket="gt_10"} 17593
telemt_pool_swap_total 164
telemt_pool_force_close_total 4881
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 54761
telemt_me_writer_removed_unexpected_total 2402
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5851
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51334
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49880
telemt_me_writer_teardown_success_total{mode="normal"} 57185
telemt_me_writer_teardown_noop_total 54762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.580008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8178816
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 185503958753 (172.76 GB)
telemt_user_octets_to_client{user="hello"} 3087293182796 (2.81 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 97878.8 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10813512
telemt_connections_bad_total 412077
telemt_connections_current 1694
telemt_connections_me_current 1694
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4515607
telemt_upstream_connect_attempt_total 46890
telemt_upstream_connect_success_total 46542
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 46881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_reconnect_attempts_total 48212
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1215
telemt_me_idle_close_by_peer_total 1214
telemt_me_route_drop_no_conn_total 3950220
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5191942
telemt_me_endpoint_quarantine_total 634
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 736
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
telemt_desync_total 28718
telemt_desync_full_logged_total 9722
telemt_desync_suppressed_total 18996
telemt_desync_frames_bucket_total{bucket="1_2"} 5802
telemt_desync_frames_bucket_total{bucket="3_10"} 11318
telemt_desync_frames_bucket_total{bucket="gt_10"} 11598
telemt_pool_swap_total 103
telemt_pool_force_close_total 3164
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 33729
telemt_me_writer_removed_unexpected_total 1276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2743
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30565
telemt_me_writer_teardown_success_total{mode="normal"} 35037
telemt_me_writer_teardown_noop_total 33736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68773
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.003497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68773
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5185240
telemt_user_connections_current{user="hello"} 1694
telemt_user_octets_from_client{user="hello"} 111924605968 (104.24 GB)
telemt_user_octets_to_client{user="hello"} 1965438717258 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 78850.8 (21h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1098627
telemt_connections_bad_total 17264
telemt_connections_current 1248
telemt_connections_me_current 1248
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 20804
telemt_upstream_connect_attempt_total 38292
telemt_upstream_connect_success_total 38181
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1740
telemt_me_reconnect_success_total 732
telemt_me_reader_eof_total 707
telemt_me_idle_close_by_peer_total 707
telemt_me_route_drop_no_conn_total 383579
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977993
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 650
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5566
telemt_desync_full_logged_total 1701
telemt_desync_suppressed_total 3865
telemt_desync_frames_bucket_total{bucket="1_2"} 1310
telemt_desync_frames_bucket_total{bucket="3_10"} 2194
telemt_desync_frames_bucket_total{bucket="gt_10"} 2062
telemt_pool_swap_total 84
telemt_pool_force_close_total 2148
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 31758
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2460
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30007
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29610
telemt_me_writer_teardown_success_total{mode="normal"} 32467
telemt_me_writer_teardown_noop_total 31761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.804767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 974444
telemt_user_connections_current{user="hello"} 1248
telemt_user_octets_from_client{user="hello"} 18090864769 (16.85 GB)
telemt_user_octets_to_client{user="hello"} 421491828811 (392.54 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 161047.7 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12644527
telemt_connections_bad_total 1468826
telemt_connections_current 2082
telemt_connections_me_current 2082
telemt_handshake_timeouts_total 351729
telemt_upstream_connect_attempt_total 60559
telemt_upstream_connect_success_total 60285
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 60471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_reconnect_attempts_total 2376
telemt_me_reconnect_success_total 1254
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 4225997
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9563346
telemt_me_endpoint_quarantine_total 1077
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1201
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
telemt_desync_total 39278
telemt_desync_full_logged_total 12822
telemt_desync_suppressed_total 26456
telemt_desync_frames_bucket_total{bucket="1_2"} 9356
telemt_desync_frames_bucket_total{bucket="3_10"} 14545
telemt_desync_frames_bucket_total{bucket="gt_10"} 15377
telemt_pool_swap_total 178
telemt_pool_force_close_total 4913
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 628
telemt_me_draining_writers_reap_progress_total 54502
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51236
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49589
telemt_me_writer_teardown_success_total{mode="normal"} 55707
telemt_me_writer_teardown_noop_total 54504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110211
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.488038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110211
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 628
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 1097
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 9532475
telemt_user_connections_current{user="hello"} 2082
telemt_user_octets_from_client{user="hello"} 186949323132 (174.11 GB)
telemt_user_octets_to_client{user="hello"} 4212075908292 (3.83 TB)
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 161044.2 (44h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10963729
telemt_connections_bad_total 1223816
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 283994
telemt_upstream_connect_attempt_total 86349
telemt_upstream_connect_success_total 85640
telemt_upstream_connect_fail_total 571
telemt_upstream_connect_attempts_per_request{bucket="1"} 86211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 571
telemt_me_reconnect_attempts_total 9078
telemt_me_reconnect_success_total 2102
telemt_me_reader_eof_total 1958
telemt_me_idle_close_by_peer_total 1958
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5472262
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8482327
telemt_me_endpoint_quarantine_total 1222
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1204
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
telemt_me_writers_active_current 46
telemt_desync_total 38668
telemt_desync_full_logged_total 12485
telemt_desync_suppressed_total 26183
telemt_desync_frames_bucket_total{bucket="1_2"} 9623
telemt_desync_frames_bucket_total{bucket="3_10"} 14398
telemt_desync_frames_bucket_total{bucket="gt_10"} 14647
telemt_pool_swap_total 170
telemt_pool_force_close_total 4752
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 53938
telemt_me_writer_removed_unexpected_total 1983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50406
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4313
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49186
telemt_me_writer_teardown_success_total{mode="normal"} 55991
telemt_me_writer_teardown_noop_total 53943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.707256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1701
telemt_me_writer_restored_fallback_total 101
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8488242
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 149258021213 (139.01 GB)
telemt_user_octets_to_client{user="hello"} 3250422821451 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 624
telemt_user_unique_ips_recent_window{user="hello"} 254
```