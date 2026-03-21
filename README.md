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

# Server Metrics 2026-03-21 20:33:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86266.3 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3076284
telemt_connections_bad_total 179648
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 95278
telemt_upstream_connect_attempt_total 35248
telemt_upstream_connect_success_total 35102
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 35205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1892
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_route_drop_no_conn_total 2623095
telemt_me_route_drop_channel_closed_total 843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2489313
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 673
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 47
telemt_desync_total 9960
telemt_desync_full_logged_total 3473
telemt_desync_suppressed_total 6487
telemt_desync_frames_bucket_total{bucket="1_2"} 2167
telemt_desync_frames_bucket_total{bucket="3_10"} 3735
telemt_desync_frames_bucket_total{bucket="gt_10"} 4058
telemt_pool_swap_total 93
telemt_pool_force_close_total 2814
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 28894
telemt_me_writer_removed_unexpected_total 715
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2427
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26080
telemt_me_writer_teardown_success_total{mode="normal"} 29349
telemt_me_writer_teardown_noop_total 28902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.069813
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2488933
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 36867355785 (34.34 GB)
telemt_user_octets_to_client{user="hello"} 634204166142 (590.65 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 11404.2 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456505
telemt_connections_bad_total 21176
telemt_connections_current 1365
telemt_connections_me_current 1365
telemt_handshake_timeouts_total 16038
telemt_upstream_connect_attempt_total 4524
telemt_upstream_connect_success_total 4433
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 307
telemt_me_reconnect_success_total 142
telemt_me_reader_eof_total 120
telemt_me_idle_close_by_peer_total 120
telemt_me_route_drop_no_conn_total 272129
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372262
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
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
telemt_me_writers_active_current 42
telemt_desync_total 1580
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 12
telemt_pool_force_close_total 363
telemt_me_writer_close_signal_drop_total 32
telemt_me_draining_writers_reap_progress_total 3937
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3709
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3574
telemt_me_writer_teardown_success_total{mode="normal"} 4044
telemt_me_writer_teardown_noop_total 3937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7981
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.107455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7981
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 32
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 371810
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 6137749940 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 109680471376 (102.15 GB)
telemt_user_unique_ips_current{user="hello"} 837
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 86263.9 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6866803
telemt_connections_bad_total 531349
telemt_connections_current 3800
telemt_connections_me_current 3800
telemt_handshake_timeouts_total 214360
telemt_upstream_connect_attempt_total 30975
telemt_upstream_connect_success_total 30913
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1329
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 4349024
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5622684
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 640
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
telemt_me_writers_active_current 46
telemt_desync_total 23189
telemt_desync_full_logged_total 7713
telemt_desync_suppressed_total 15476
telemt_desync_frames_bucket_total{bucket="1_2"} 4844
telemt_desync_frames_bucket_total{bucket="3_10"} 9224
telemt_desync_frames_bucket_total{bucket="gt_10"} 9121
telemt_pool_swap_total 92
telemt_pool_force_close_total 3091
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 500
telemt_me_draining_writers_reap_progress_total 28184
telemt_me_writer_removed_unexpected_total 652
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2420
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25093
telemt_me_writer_teardown_success_total{mode="normal"} 28467
telemt_me_writer_teardown_noop_total 28221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 137.923134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 500
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 5615934
telemt_user_connections_current{user="hello"} 3800
telemt_user_octets_from_client{user="hello"} 95438026000 (88.88 GB)
telemt_user_octets_to_client{user="hello"} 1763796182244 (1.60 TB)
telemt_user_unique_ips_current{user="hello"} 1584
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 86266.2 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5560783
telemt_connections_bad_total 538776
telemt_connections_current 3322
telemt_connections_me_current 3322
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 182889
telemt_upstream_connect_attempt_total 35065
telemt_upstream_connect_success_total 34747
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 34911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1669
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 1925321
telemt_me_route_drop_channel_closed_total 220
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4161612
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_me_writers_active_current 44
telemt_desync_total 19757
telemt_desync_full_logged_total 6540
telemt_desync_suppressed_total 13217
telemt_desync_frames_bucket_total{bucket="1_2"} 4833
telemt_desync_frames_bucket_total{bucket="3_10"} 7651
telemt_desync_frames_bucket_total{bucket="gt_10"} 7273
telemt_pool_swap_total 94
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 26960
telemt_me_writer_removed_unexpected_total 649
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24110
telemt_me_writer_teardown_success_total{mode="normal"} 27538
telemt_me_writer_teardown_noop_total 26965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.860833
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54503
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4154330
telemt_user_connections_current{user="hello"} 3322
telemt_user_octets_from_client{user="hello"} 125127132129 (116.53 GB)
telemt_user_octets_to_client{user="hello"} 1900485633895 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1309
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 86229.3 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5485468
telemt_connections_bad_total 496463
telemt_connections_current 3120
telemt_connections_me_current 3120
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 166667
telemt_upstream_connect_attempt_total 41484
telemt_upstream_connect_success_total 41216
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1037
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1722
telemt_me_reconnect_success_total 756
telemt_me_reader_eof_total 700
telemt_me_idle_close_by_peer_total 700
telemt_me_route_drop_no_conn_total 1979267
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4144029
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 641
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
telemt_me_writers_active_current 43
telemt_desync_total 19532
telemt_desync_full_logged_total 6377
telemt_desync_suppressed_total 13155
telemt_desync_frames_bucket_total{bucket="1_2"} 4878
telemt_desync_frames_bucket_total{bucket="3_10"} 7399
telemt_desync_frames_bucket_total{bucket="gt_10"} 7255
telemt_pool_swap_total 92
telemt_pool_force_close_total 2714
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 28386
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 212
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25672
telemt_me_writer_teardown_success_total{mode="normal"} 29077
telemt_me_writer_teardown_noop_total 28396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.116038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4146179
telemt_user_connections_current{user="hello"} 3120
telemt_user_octets_from_client{user="hello"} 121275427655 (112.95 GB)
telemt_user_octets_to_client{user="hello"} 1890654851631 (1.72 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1269
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 86269.1 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19024228
telemt_connections_bad_total 1225324
telemt_connections_current 4111
telemt_connections_me_current 4111
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 531005
telemt_upstream_connect_attempt_total 174586
telemt_upstream_connect_success_total 157697
telemt_upstream_connect_fail_total 15499
telemt_upstream_connect_attempts_per_request{bucket="1"} 173196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8823
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15499
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59401
telemt_me_reconnect_success_total 1770
telemt_me_reader_eof_total 1194
telemt_me_idle_close_by_peer_total 1193
telemt_me_route_drop_no_conn_total 38940728
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15660038
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 220
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 220
telemt_me_single_endpoint_shadow_rotate_total 669
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
telemt_me_writers_active_current 44
telemt_desync_total 29222
telemt_desync_full_logged_total 8609
telemt_desync_suppressed_total 20613
telemt_desync_frames_bucket_total{bucket="1_2"} 6387
telemt_desync_frames_bucket_total{bucket="3_10"} 12945
telemt_desync_frames_bucket_total{bucket="gt_10"} 9890
telemt_pool_swap_total 88
telemt_pool_force_close_total 2942
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 665
telemt_me_draining_writers_reap_progress_total 26545
telemt_me_writer_removed_unexpected_total 1660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3541
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23603
telemt_me_writer_teardown_success_total{mode="normal"} 27948
telemt_me_writer_teardown_noop_total 26568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54516
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.458091
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54516
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 665
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1227
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 11365
telemt_me_writer_removed_unexpected_minus_restored_total 421
telemt_user_connections_total{user="hello"} 15779360
telemt_user_connections_current{user="hello"} 4111
telemt_user_octets_from_client{user="hello"} 149353819139 (139.10 GB)
telemt_user_octets_to_client{user="hello"} 963301754631 (897.14 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1611
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 86236.0 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5391205
telemt_connections_bad_total 521442
telemt_connections_current 3176
telemt_connections_me_current 3176
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 111382
telemt_upstream_connect_attempt_total 44598
telemt_upstream_connect_success_total 44114
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 44514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_reconnect_attempts_total 11065
telemt_me_reconnect_success_total 1265
telemt_me_reader_eof_total 1196
telemt_me_idle_close_by_peer_total 1196
telemt_me_route_drop_no_conn_total 2255059
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4183334
telemt_me_endpoint_quarantine_total 528
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 640
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 20719
telemt_desync_full_logged_total 7193
telemt_desync_suppressed_total 13526
telemt_desync_frames_bucket_total{bucket="1_2"} 3966
telemt_desync_frames_bucket_total{bucket="3_10"} 8076
telemt_desync_frames_bucket_total{bucket="gt_10"} 8677
telemt_pool_swap_total 87
telemt_pool_force_close_total 2575
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 316
telemt_me_draining_writers_reap_progress_total 29200
telemt_me_writer_removed_unexpected_total 1176
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27416
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26625
telemt_me_writer_teardown_success_total{mode="normal"} 30389
telemt_me_writer_teardown_noop_total 29201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.275181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 316
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1071
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4173303
telemt_user_connections_current{user="hello"} 3176
telemt_user_octets_from_client{user="hello"} 111071860413 (103.44 GB)
telemt_user_octets_to_client{user="hello"} 1690600077363 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1321
telemt_user_unique_ips_recent_window{user="hello"} 421
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 23071.8 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3084330
telemt_connections_bad_total 114358
telemt_connections_current 2962
telemt_connections_me_current 2962
telemt_handshake_timeouts_total 1331119
telemt_upstream_connect_attempt_total 7474
telemt_upstream_connect_success_total 7372
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 7468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 2196
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 900318
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1462417
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 8052
telemt_desync_full_logged_total 2659
telemt_desync_suppressed_total 5393
telemt_desync_frames_bucket_total{bucket="1_2"} 1440
telemt_desync_frames_bucket_total{bucket="3_10"} 3048
telemt_desync_frames_bucket_total{bucket="gt_10"} 3564
telemt_pool_swap_total 24
telemt_pool_force_close_total 784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 6516
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 622
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6116
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5732
telemt_me_writer_teardown_success_total{mode="normal"} 6738
telemt_me_writer_teardown_noop_total 6516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.046899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 207
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1458220
telemt_user_connections_current{user="hello"} 2962
telemt_user_octets_from_client{user="hello"} 44042480708 (41.02 GB)
telemt_user_octets_to_client{user="hello"} 600568176720 (559.32 GB)
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 4043.0 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44048
telemt_connections_bad_total 141
telemt_connections_current 665
telemt_connections_me_current 665
telemt_handshake_timeouts_total 765
telemt_upstream_connect_attempt_total 1784
telemt_upstream_connect_success_total 1778
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 13200
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40322
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 285
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 4
telemt_pool_force_close_total 111
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1524
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1413
telemt_me_writer_teardown_success_total{mode="normal"} 1543
telemt_me_writer_teardown_noop_total 1524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.205301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 40256
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 996589280 (950.42 MB)
telemt_user_octets_to_client{user="hello"} 33867591700 (31.54 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 86240.5 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6400761
telemt_connections_bad_total 657954
telemt_connections_current 3591
telemt_connections_me_current 3591
telemt_handshake_timeouts_total 185597
telemt_upstream_connect_attempt_total 32696
telemt_upstream_connect_success_total 32565
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1392
telemt_me_reconnect_success_total 699
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1983194
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4907576
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 654
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 18651
telemt_desync_full_logged_total 6205
telemt_desync_suppressed_total 12446
telemt_desync_frames_bucket_total{bucket="1_2"} 4548
telemt_desync_frames_bucket_total{bucket="3_10"} 6806
telemt_desync_frames_bucket_total{bucket="gt_10"} 7297
telemt_pool_swap_total 95
telemt_pool_force_close_total 2592
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 327
telemt_me_draining_writers_reap_progress_total 29351
telemt_me_writer_removed_unexpected_total 657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2388
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27627
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26759
telemt_me_writer_teardown_success_total{mode="normal"} 30015
telemt_me_writer_teardown_noop_total 29353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.620552
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 327
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4883495
telemt_user_connections_current{user="hello"} 3591
telemt_user_octets_from_client{user="hello"} 97131974140 (90.46 GB)
telemt_user_octets_to_client{user="hello"} 2270954092256 (2.07 TB)
telemt_user_unique_ips_current{user="hello"} 1344
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 86237.1 (23h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5424546
telemt_connections_bad_total 506297
telemt_connections_current 3442
telemt_connections_me_current 3442
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 155399
telemt_upstream_connect_attempt_total 49134
telemt_upstream_connect_success_total 48772
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 49075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 4479
telemt_me_reconnect_success_total 989
telemt_me_reader_eof_total 876
telemt_me_idle_close_by_peer_total 876
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 2035545
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4274614
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 655
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
telemt_me_writers_active_current 46
telemt_desync_total 17347
telemt_desync_full_logged_total 5842
telemt_desync_suppressed_total 11505
telemt_desync_frames_bucket_total{bucket="1_2"} 4292
telemt_desync_frames_bucket_total{bucket="3_10"} 6380
telemt_desync_frames_bucket_total{bucket="gt_10"} 6675
telemt_pool_swap_total 93
telemt_pool_force_close_total 2520
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 326
telemt_me_draining_writers_reap_progress_total 28608
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26088
telemt_me_writer_teardown_success_total{mode="normal"} 29535
telemt_me_writer_teardown_noop_total 28610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.711387
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 326
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4279000
telemt_user_connections_current{user="hello"} 3442
telemt_user_octets_from_client{user="hello"} 81733491721 (76.12 GB)
telemt_user_octets_to_client{user="hello"} 1789580941360 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1333
telemt_user_unique_ips_recent_window{user="hello"} 400
```