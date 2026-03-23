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

# Server Metrics 2026-03-23 06:37:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 120659.4 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4346641
telemt_connections_bad_total 414382
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_handshake_timeouts_total 149036
telemt_upstream_connect_attempt_total 44751
telemt_upstream_connect_success_total 44750
telemt_upstream_connect_attempts_per_request{bucket="1"} 44750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1560
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 729
telemt_me_idle_close_by_peer_total 729
telemt_me_route_drop_no_conn_total 3583784
telemt_me_route_drop_channel_closed_total 1391
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3553215
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 943
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_warm_current 26
telemt_desync_total 14750
telemt_desync_full_logged_total 4687
telemt_desync_suppressed_total 10063
telemt_desync_frames_bucket_total{bucket="1_2"} 3808
telemt_desync_frames_bucket_total{bucket="3_10"} 5518
telemt_desync_frames_bucket_total{bucket="gt_10"} 5424
telemt_pool_swap_total 133
telemt_pool_force_close_total 4102
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 786
telemt_me_draining_writers_reap_progress_total 40980
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2948
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38304
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36878
telemt_me_writer_teardown_success_total{mode="normal"} 41252
telemt_me_writer_teardown_noop_total 40993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82245
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 454.713948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82245
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 786
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 3540422
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 46774627424 (43.56 GB)
telemt_user_octets_to_client{user="hello"} 921414776484 (858.13 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 134026.0 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4227042
telemt_connections_bad_total 393719
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 111922
telemt_upstream_connect_attempt_total 83274
telemt_upstream_connect_success_total 82277
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 83162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11162
telemt_me_reconnect_success_total 4036
telemt_me_reader_eof_total 4008
telemt_me_idle_close_by_peer_total 4007
telemt_me_route_drop_no_conn_total 3689818
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3351831
telemt_me_endpoint_quarantine_total 1085
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1055
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
telemt_me_writers_active_current 96
telemt_desync_total 13865
telemt_desync_full_logged_total 7830
telemt_desync_suppressed_total 6035
telemt_desync_frames_bucket_total{bucket="1_2"} 3137
telemt_desync_frames_bucket_total{bucket="3_10"} 5437
telemt_desync_frames_bucket_total{bucket="gt_10"} 5291
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 56371
telemt_me_writer_removed_unexpected_total 3926
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7089
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53255
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52879
telemt_me_writer_teardown_success_total{mode="normal"} 60344
telemt_me_writer_teardown_noop_total 56372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116716
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.031794
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116716
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 3576
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 3366171
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 45424727643 (42.31 GB)
telemt_user_octets_to_client{user="hello"} 855253734281 (796.52 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 208886.2 (58h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16848055
telemt_connections_bad_total 1712874
telemt_connections_current 2305
telemt_connections_me_current 2305
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 417703
telemt_upstream_connect_attempt_total 93812
telemt_upstream_connect_success_total 93701
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1736
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3326
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1708
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 14163170
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13380642
telemt_me_endpoint_quarantine_total 1413
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1581
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_me_writers_warm_current 31
telemt_desync_total 56203
telemt_desync_full_logged_total 17969
telemt_desync_suppressed_total 38234
telemt_desync_frames_bucket_total{bucket="1_2"} 12482
telemt_desync_frames_bucket_total{bucket="3_10"} 22024
telemt_desync_frames_bucket_total{bucket="gt_10"} 21697
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1116
telemt_me_draining_writers_reap_progress_total 72362
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67205
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65162
telemt_me_writer_teardown_success_total{mode="normal"} 73289
telemt_me_writer_teardown_noop_total 72416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.982815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1116
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1521
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13380383
telemt_user_connections_current{user="hello"} 2305
telemt_user_octets_from_client{user="hello"} 202452028725 (188.55 GB)
telemt_user_octets_to_client{user="hello"} 3652554120271 (3.32 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 208887.2 (58h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12299245
telemt_connections_bad_total 1311716
telemt_connections_current 1418
telemt_connections_me_current 1418
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 356422
telemt_upstream_connect_attempt_total 107991
telemt_upstream_connect_success_total 106576
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 107477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4771
telemt_me_reconnect_success_total 2059
telemt_me_reader_eof_total 1915
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 4641473
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9094249
telemt_me_endpoint_quarantine_total 1425
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1596
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_me_writers_warm_current 4
telemt_desync_total 40010
telemt_desync_full_logged_total 13541
telemt_desync_suppressed_total 26469
telemt_desync_frames_bucket_total{bucket="1_2"} 9920
telemt_desync_frames_bucket_total{bucket="3_10"} 15358
telemt_desync_frames_bucket_total{bucket="gt_10"} 14732
telemt_pool_swap_total 223
telemt_pool_force_close_total 6583
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 725
telemt_me_draining_writers_reap_progress_total 70345
telemt_me_writer_removed_unexpected_total 1944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66002
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63762
telemt_me_writer_teardown_success_total{mode="normal"} 72153
telemt_me_writer_teardown_noop_total 70370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142523
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.117359
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142523
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 725
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9031736
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 221332379244 (206.13 GB)
telemt_user_octets_to_client{user="hello"} 4059673276235 (3.69 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 208850.6 (58h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11430625
telemt_connections_bad_total 1052484
telemt_connections_current 1167
telemt_connections_me_current 1167
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 362841
telemt_upstream_connect_attempt_total 92441
telemt_upstream_connect_success_total 90851
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 91056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44875
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5955
telemt_me_reconnect_success_total 2519
telemt_me_reader_eof_total 2256
telemt_me_idle_close_by_peer_total 2255
telemt_me_route_drop_no_conn_total 5408930
telemt_me_route_drop_channel_closed_total 390
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8593121
telemt_me_endpoint_quarantine_total 1478
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1560
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_me_writers_warm_current 8
telemt_desync_total 39097
telemt_desync_full_logged_total 13009
telemt_desync_suppressed_total 26088
telemt_desync_frames_bucket_total{bucket="1_2"} 9860
telemt_desync_frames_bucket_total{bucket="3_10"} 14958
telemt_desync_frames_bucket_total{bucket="gt_10"} 14279
telemt_pool_swap_total 219
telemt_pool_force_close_total 6470
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 769
telemt_me_draining_writers_reap_progress_total 70976
telemt_me_writer_removed_unexpected_total 2401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66414
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64506
telemt_me_writer_teardown_success_total{mode="normal"} 73314
telemt_me_writer_teardown_noop_total 71047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.556228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 769
telemt_me_refill_failed_total 182
telemt_me_writer_restored_same_endpoint_total 2187
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 8584830
telemt_user_connections_current{user="hello"} 1167
telemt_user_octets_from_client{user="hello"} 194954306975 (181.57 GB)
telemt_user_octets_to_client{user="hello"} 3561977443365 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 79130.6 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11903936
telemt_connections_bad_total 725691
telemt_connections_current 2396
telemt_connections_me_current 2396
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 339036
telemt_upstream_connect_attempt_total 72806
telemt_upstream_connect_success_total 69047
telemt_upstream_connect_fail_total 2457
telemt_upstream_connect_attempts_per_request{bucket="1"} 71504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6060
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2457
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8651
telemt_me_reconnect_success_total 1614
telemt_me_reader_eof_total 1030
telemt_me_idle_close_by_peer_total 1029
telemt_me_route_drop_no_conn_total 25443951
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9815113
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 215
telemt_me_single_endpoint_outage_reconnect_success_total 58
telemt_me_single_endpoint_quarantine_bypass_total 215
telemt_me_single_endpoint_shadow_rotate_total 633
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
telemt_me_writers_active_current 48
telemt_desync_total 17666
telemt_desync_full_logged_total 4975
telemt_desync_suppressed_total 12691
telemt_desync_frames_bucket_total{bucket="1_2"} 3439
telemt_desync_frames_bucket_total{bucket="3_10"} 7217
telemt_desync_frames_bucket_total{bucket="gt_10"} 7010
telemt_pool_swap_total 81
telemt_pool_force_close_total 2505
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 26222
telemt_me_writer_removed_unexpected_total 1484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3383
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 352
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23717
telemt_me_writer_teardown_success_total{mode="normal"} 27652
telemt_me_writer_teardown_noop_total 26241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.487158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3157
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9846228
telemt_user_connections_current{user="hello"} 2396
telemt_user_octets_from_client{user="hello"} 92653019900 (86.29 GB)
telemt_user_octets_to_client{user="hello"} 783423792472 (729.62 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 804
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 208857.4 (58h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11436330
telemt_connections_bad_total 1009366
telemt_connections_current 1530
telemt_connections_me_current 1530
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 261155
telemt_upstream_connect_attempt_total 121745
telemt_upstream_connect_success_total 120448
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 121566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73763
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3041
telemt_me_idle_close_by_peer_total 3038
telemt_me_route_drop_no_conn_total 5360622
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8998895
telemt_me_endpoint_quarantine_total 1431
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1588
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_warm_current 14
telemt_desync_total 47774
telemt_desync_full_logged_total 16448
telemt_desync_suppressed_total 31326
telemt_desync_frames_bucket_total{bucket="1_2"} 9728
telemt_desync_frames_bucket_total{bucket="3_10"} 18299
telemt_desync_frames_bucket_total{bucket="gt_10"} 19747
telemt_pool_swap_total 214
telemt_pool_force_close_total 6170
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 75343
telemt_me_writer_removed_unexpected_total 3057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7482
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70966
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 770
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69173
telemt_me_writer_teardown_success_total{mode="normal"} 78448
telemt_me_writer_teardown_noop_total 75344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.507667
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2832
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 9001472
telemt_user_connections_current{user="hello"} 1530
telemt_user_octets_from_client{user="hello"} 200419512361 (186.66 GB)
telemt_user_octets_to_client{user="hello"} 3450057988760 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 145693.7 (40h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12260629
telemt_connections_bad_total 508592
telemt_connections_current 1364
telemt_connections_me_current 1364
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4936654
telemt_upstream_connect_attempt_total 70434
telemt_upstream_connect_success_total 69931
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 70421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_reconnect_attempts_total 49489
telemt_me_reconnect_success_total 2013
telemt_me_reader_eof_total 1693
telemt_me_idle_close_by_peer_total 1692
telemt_me_route_drop_no_conn_total 4175102
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5890138
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1124
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33159
telemt_desync_full_logged_total 11377
telemt_desync_suppressed_total 21782
telemt_desync_frames_bucket_total{bucket="1_2"} 6671
telemt_desync_frames_bucket_total{bucket="3_10"} 13044
telemt_desync_frames_bucket_total{bucket="gt_10"} 13444
telemt_pool_swap_total 155
telemt_pool_force_close_total 4363
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 55073
telemt_me_writer_removed_unexpected_total 1728
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3917
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50710
telemt_me_writer_teardown_success_total{mode="normal"} 56861
telemt_me_writer_teardown_noop_total 55080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111941
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.114871
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111941
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 2758
telemt_me_writer_restored_same_endpoint_total 1776
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5881934
telemt_user_connections_current{user="hello"} 1364
telemt_user_octets_from_client{user="hello"} 122895777080 (114.46 GB)
telemt_user_octets_to_client{user="hello"} 2295740269766 (2.09 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 126664.5 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1828520
telemt_connections_bad_total 37826
telemt_connections_current 1076
telemt_connections_me_current 1076
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 40494
telemt_upstream_connect_attempt_total 59228
telemt_upstream_connect_success_total 59029
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 59189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 874
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 2565
telemt_me_reconnect_success_total 1039
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 727608
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1625752
telemt_me_endpoint_quarantine_total 1069
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1041
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
telemt_desync_total 10802
telemt_desync_full_logged_total 3048
telemt_desync_suppressed_total 7754
telemt_desync_frames_bucket_total{bucket="1_2"} 3436
telemt_desync_frames_bucket_total{bucket="3_10"} 4037
telemt_desync_frames_bucket_total{bucket="gt_10"} 3329
telemt_pool_swap_total 137
telemt_pool_force_close_total 3473
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 180
telemt_me_draining_writers_reap_progress_total 50556
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47083
telemt_me_writer_teardown_success_total{mode="normal"} 51603
telemt_me_writer_teardown_noop_total 50560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102163
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.754452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102163
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 180
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 892
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1621276
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 28537463473 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 630763135315 (587.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 208862.3 (58h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13719835
telemt_connections_bad_total 1668157
telemt_connections_current 1675
telemt_connections_me_current 1675
telemt_handshake_timeouts_total 402497
telemt_upstream_connect_attempt_total 84354
telemt_upstream_connect_success_total 83985
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 84217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3313
telemt_me_reconnect_success_total 1658
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 4562346
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10344159
telemt_me_endpoint_quarantine_total 1545
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1588
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_warm_current 21
telemt_desync_total 43574
telemt_desync_full_logged_total 14175
telemt_desync_suppressed_total 29399
telemt_desync_frames_bucket_total{bucket="1_2"} 10602
telemt_desync_frames_bucket_total{bucket="3_10"} 16027
telemt_desync_frames_bucket_total{bucket="gt_10"} 16945
telemt_pool_swap_total 231
telemt_pool_force_close_total 6017
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 714
telemt_me_draining_writers_reap_progress_total 76353
telemt_me_writer_removed_unexpected_total 1577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72135
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5843
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70336
telemt_me_writer_teardown_success_total{mode="normal"} 77993
telemt_me_writer_teardown_noop_total 76355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 154215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154348
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.200032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154348
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 714
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1457
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10310464
telemt_user_connections_current{user="hello"} 1675
telemt_user_octets_from_client{user="hello"} 198195890416 (184.58 GB)
telemt_user_octets_to_client{user="hello"} 4604659571180 (4.19 TB)
telemt_user_unique_ips_current{user="hello"} 617
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 208859.0 (58h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12044934
telemt_connections_bad_total 1429523
telemt_connections_current 1555
telemt_connections_me_current 1555
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 323582
telemt_upstream_connect_attempt_total 112358
telemt_upstream_connect_success_total 111397
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 112149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11221
telemt_me_reconnect_success_total 2806
telemt_me_reader_eof_total 2602
telemt_me_idle_close_by_peer_total 2601
telemt_me_seq_mismatch_total 113
telemt_me_route_drop_no_conn_total 5731659
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9262244
telemt_me_endpoint_quarantine_total 1735
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1590
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_me_writers_warm_current 19
telemt_desync_total 43516
telemt_desync_full_logged_total 13899
telemt_desync_suppressed_total 29617
telemt_desync_frames_bucket_total{bucket="1_2"} 11262
telemt_desync_frames_bucket_total{bucket="3_10"} 16104
telemt_desync_frames_bucket_total{bucket="gt_10"} 16150
telemt_pool_swap_total 221
telemt_pool_force_close_total 5763
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 76836
telemt_me_writer_removed_unexpected_total 2636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7276
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72304
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 71073
telemt_me_writer_teardown_success_total{mode="normal"} 79580
telemt_me_writer_teardown_noop_total 76841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 153658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 155480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 156036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 156371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 156421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 156421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.072478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 156421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 437
telemt_me_writer_restored_same_endpoint_total 2234
telemt_me_writer_restored_fallback_total 148
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 9266456
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 160754743248 (149.71 GB)
telemt_user_octets_to_client{user="hello"} 3627314487570 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 188
```