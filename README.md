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

# Server Metrics 2026-03-23 03:13:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 108397.8 (30h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3706596
telemt_connections_bad_total 356350
telemt_connections_current 1151
telemt_connections_me_current 1151
telemt_handshake_timeouts_total 119865
telemt_upstream_connect_attempt_total 40458
telemt_upstream_connect_success_total 40457
telemt_upstream_connect_attempts_per_request{bucket="1"} 40457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26226
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1429
telemt_me_reconnect_success_total 631
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 3010422
telemt_me_route_drop_channel_closed_total 1237
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3028905
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 771
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 848
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
telemt_me_writers_active_current 44
telemt_desync_total 13025
telemt_desync_full_logged_total 4141
telemt_desync_suppressed_total 8884
telemt_desync_frames_bucket_total{bucket="1_2"} 3448
telemt_desync_frames_bucket_total{bucket="3_10"} 4760
telemt_desync_frames_bucket_total{bucket="gt_10"} 4817
telemt_pool_swap_total 120
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 37058
telemt_me_writer_removed_unexpected_total 625
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34695
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33396
telemt_me_writer_teardown_success_total{mode="normal"} 37331
telemt_me_writer_teardown_noop_total 37069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.597929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 566
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3017784
telemt_user_connections_current{user="hello"} 1151
telemt_user_octets_from_client{user="hello"} 42854943120 (39.91 GB)
telemt_user_octets_to_client{user="hello"} 822623424644 (766.13 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 121763.5 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4043267
telemt_connections_bad_total 372734
telemt_connections_current 195
telemt_connections_me_current 195
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101703
telemt_upstream_connect_attempt_total 76746
telemt_upstream_connect_success_total 75825
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 76639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10512
telemt_me_reconnect_success_total 3745
telemt_me_reader_eof_total 3726
telemt_me_idle_close_by_peer_total 3726
telemt_me_route_drop_no_conn_total 3647145
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3211810
telemt_me_endpoint_quarantine_total 990
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 959
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 13106
telemt_desync_full_logged_total 7361
telemt_desync_suppressed_total 5745
telemt_desync_frames_bucket_total{bucket="1_2"} 2982
telemt_desync_frames_bucket_total{bucket="3_10"} 5139
telemt_desync_frames_bucket_total{bucket="gt_10"} 4985
telemt_pool_swap_total 115
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50675
telemt_me_writer_removed_unexpected_total 3651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47831
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47475
telemt_me_writer_teardown_success_total{mode="normal"} 54364
telemt_me_writer_teardown_noop_total 50676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105040
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.686395
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105040
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 265
telemt_me_writer_restored_same_endpoint_total 3318
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 302
telemt_user_connections_total{user="hello"} 3226297
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 43367156243 (40.39 GB)
telemt_user_octets_to_client{user="hello"} 801310301273 (746.28 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 196623.5 (54h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16446964
telemt_connections_bad_total 1669742
telemt_connections_current 999
telemt_connections_me_current 999
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399695
telemt_upstream_connect_attempt_total 88590
telemt_upstream_connect_success_total 88483
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3057
telemt_me_reconnect_success_total 1630
telemt_me_reader_eof_total 1580
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 14062599
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13054988
telemt_me_endpoint_quarantine_total 1323
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1485
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
telemt_me_writers_active_current 43
telemt_desync_total 54202
telemt_desync_full_logged_total 17270
telemt_desync_suppressed_total 36932
telemt_desync_frames_bucket_total{bucket="1_2"} 12094
telemt_desync_frames_bucket_total{bucket="3_10"} 21169
telemt_desync_frames_bucket_total{bucket="gt_10"} 20939
telemt_pool_swap_total 213
telemt_pool_force_close_total 6903
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1072
telemt_me_draining_writers_reap_progress_total 67710
telemt_me_writer_removed_unexpected_total 1518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5707
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62802
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6433
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60807
telemt_me_writer_teardown_success_total{mode="normal"} 68509
telemt_me_writer_teardown_noop_total 67763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.010234
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1072
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 13054946
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 197991929117 (184.39 GB)
telemt_user_octets_to_client{user="hello"} 3522619465631 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 196624.8 (54h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11985951
telemt_connections_bad_total 1258480
telemt_connections_current 722
telemt_connections_me_current 722
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345784
telemt_upstream_connect_attempt_total 102850
telemt_upstream_connect_success_total 101512
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 102397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4530
telemt_me_reconnect_success_total 1945
telemt_me_reader_eof_total 1811
telemt_me_idle_close_by_peer_total 1811
telemt_me_route_drop_no_conn_total 4568490
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8880513
telemt_me_endpoint_quarantine_total 1339
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39118
telemt_desync_full_logged_total 13175
telemt_desync_suppressed_total 25943
telemt_desync_frames_bucket_total{bucket="1_2"} 9686
telemt_desync_frames_bucket_total{bucket="3_10"} 15026
telemt_desync_frames_bucket_total{bucket="gt_10"} 14406
telemt_pool_swap_total 210
telemt_pool_force_close_total 6251
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 65808
telemt_me_writer_removed_unexpected_total 1838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5798
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61707
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5739
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59557
telemt_me_writer_teardown_success_total{mode="normal"} 67505
telemt_me_writer_teardown_noop_total 65833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133338
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.553377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133338
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8818217
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 218404902468 (203.41 GB)
telemt_user_octets_to_client{user="hello"} 3983686207395 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 196588.8 (54h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11138792
telemt_connections_bad_total 996926
telemt_connections_current 525
telemt_connections_me_current 525
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346387
telemt_upstream_connect_attempt_total 87292
telemt_upstream_connect_success_total 85726
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5820
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2170
telemt_me_idle_close_by_peer_total 2169
telemt_me_route_drop_no_conn_total 5347481
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8405975
telemt_me_endpoint_quarantine_total 1385
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1463
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_me_writers_active_current 46
telemt_desync_total 38329
telemt_desync_full_logged_total 12709
telemt_desync_suppressed_total 25620
telemt_desync_frames_bucket_total{bucket="1_2"} 9683
telemt_desync_frames_bucket_total{bucket="3_10"} 14678
telemt_desync_frames_bucket_total{bucket="gt_10"} 13968
telemt_pool_swap_total 206
telemt_pool_force_close_total 6142
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 66349
telemt_me_writer_removed_unexpected_total 2318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62065
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5571
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60207
telemt_me_writer_teardown_success_total{mode="normal"} 68601
telemt_me_writer_teardown_noop_total 66420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.877497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 8397872
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 193125840475 (179.86 GB)
telemt_user_octets_to_client{user="hello"} 3485953072089 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66869.2 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11375627
telemt_connections_bad_total 671252
telemt_connections_current 1160
telemt_connections_me_current 1160
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 289553
telemt_upstream_connect_attempt_total 61765
telemt_upstream_connect_success_total 58581
telemt_upstream_connect_fail_total 2059
telemt_upstream_connect_attempts_per_request{bucket="1"} 60640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21035
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6020
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2059
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7916
telemt_me_reconnect_success_total 1342
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 25310948
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9431255
telemt_me_endpoint_quarantine_total 503
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 535
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
telemt_desync_total 16672
telemt_desync_full_logged_total 4577
telemt_desync_suppressed_total 12095
telemt_desync_frames_bucket_total{bucket="1_2"} 3172
telemt_desync_frames_bucket_total{bucket="3_10"} 6800
telemt_desync_frames_bucket_total{bucket="gt_10"} 6700
telemt_pool_swap_total 69
telemt_pool_force_close_total 2193
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 21982
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19789
telemt_me_writer_teardown_success_total{mode="normal"} 23161
telemt_me_writer_teardown_noop_total 22001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.059651
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 885
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 9457063
telemt_user_connections_current{user="hello"} 1160
telemt_user_octets_from_client{user="hello"} 87939000162 (81.90 GB)
telemt_user_octets_to_client{user="hello"} 639206599038 (595.31 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 196595.4 (54h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11093872
telemt_connections_bad_total 967557
telemt_connections_current 1065
telemt_connections_me_current 1065
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244649
telemt_upstream_connect_attempt_total 116109
telemt_upstream_connect_success_total 114921
telemt_upstream_connect_fail_total 1013
telemt_upstream_connect_attempts_per_request{bucket="1"} 115934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1013
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73203
telemt_me_reconnect_success_total 3164
telemt_me_reader_eof_total 2863
telemt_me_idle_close_by_peer_total 2860
telemt_me_route_drop_no_conn_total 5277554
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8742945
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1492
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
telemt_me_writers_active_current 47
telemt_desync_total 46584
telemt_desync_full_logged_total 15990
telemt_desync_suppressed_total 30594
telemt_desync_frames_bucket_total{bucket="1_2"} 9467
telemt_desync_frames_bucket_total{bucket="3_10"} 17834
telemt_desync_frames_bucket_total{bucket="gt_10"} 19283
telemt_pool_swap_total 202
telemt_pool_force_close_total 5860
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 70366
telemt_me_writer_removed_unexpected_total 2883
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7082
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64506
telemt_me_writer_teardown_success_total{mode="normal"} 73293
telemt_me_writer_teardown_noop_total 70367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143660
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.319256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143660
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2667
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8745806
telemt_user_connections_current{user="hello"} 1065
telemt_user_octets_from_client{user="hello"} 196591503273 (183.09 GB)
telemt_user_octets_to_client{user="hello"} 3341195697060 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 438
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 133431.6 (37h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11814719
telemt_connections_bad_total 484124
telemt_connections_current 617
telemt_connections_me_current 617
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4787407
telemt_upstream_connect_attempt_total 64813
telemt_upstream_connect_success_total 64344
telemt_upstream_connect_fail_total 456
telemt_upstream_connect_attempts_per_request{bucket="1"} 64800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 456
telemt_me_reconnect_attempts_total 49168
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1579
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 4105674
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5676399
telemt_me_endpoint_quarantine_total 919
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1028
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31891
telemt_desync_full_logged_total 10905
telemt_desync_suppressed_total 20986
telemt_desync_frames_bucket_total{bucket="1_2"} 6366
telemt_desync_frames_bucket_total{bucket="3_10"} 12582
telemt_desync_frames_bucket_total{bucket="gt_10"} 12943
telemt_pool_swap_total 142
telemt_pool_force_close_total 4067
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 49988
telemt_me_writer_removed_unexpected_total 1623
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47639
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45921
telemt_me_writer_teardown_success_total{mode="normal"} 51661
telemt_me_writer_teardown_noop_total 49995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101656
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.756353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101656
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 2746
telemt_me_writer_restored_same_endpoint_total 1681
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5668468
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 120456498032 (112.18 GB)
telemt_user_octets_to_client{user="hello"} 2207683123694 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 114402.5 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1578039
telemt_connections_bad_total 36988
telemt_connections_current 467
telemt_connections_me_current 467
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32478
telemt_upstream_connect_attempt_total 54211
telemt_upstream_connect_success_total 54042
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 54183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 530175
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1402835
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 946
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_warm_current 42
telemt_desync_total 9852
telemt_desync_full_logged_total 2787
telemt_desync_suppressed_total 7065
telemt_desync_frames_bucket_total{bucket="1_2"} 3064
telemt_desync_frames_bucket_total{bucket="3_10"} 3722
telemt_desync_frames_bucket_total{bucket="gt_10"} 3066
telemt_pool_swap_total 124
telemt_pool_force_close_total 3099
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 46064
telemt_me_writer_removed_unexpected_total 921
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42965
telemt_me_writer_teardown_success_total{mode="normal"} 47027
telemt_me_writer_teardown_noop_total 46068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.451263
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1398570
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 26517741777 (24.70 GB)
telemt_user_octets_to_client{user="hello"} 589758909799 (549.26 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 196600.0 (54h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13414796
telemt_connections_bad_total 1626843
telemt_connections_current 745
telemt_connections_me_current 745
telemt_handshake_timeouts_total 391569
telemt_upstream_connect_attempt_total 78720
telemt_upstream_connect_success_total 78365
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 78584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3081
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1543
telemt_me_idle_close_by_peer_total 1543
telemt_me_route_drop_no_conn_total 4493170
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10101574
telemt_me_endpoint_quarantine_total 1439
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1491
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42370
telemt_desync_full_logged_total 13843
telemt_desync_suppressed_total 28527
telemt_desync_frames_bucket_total{bucket="1_2"} 10301
telemt_desync_frames_bucket_total{bucket="3_10"} 15564
telemt_desync_frames_bucket_total{bucket="gt_10"} 16505
telemt_pool_swap_total 218
telemt_pool_force_close_total 5726
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 71247
telemt_me_writer_removed_unexpected_total 1478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65521
telemt_me_writer_teardown_success_total{mode="normal"} 72780
telemt_me_writer_teardown_noop_total 71249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 143137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 144016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144029
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.856568
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144029
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1370
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10068201
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 195247874484 (181.84 GB)
telemt_user_octets_to_client{user="hello"} 4477614485220 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 196596.4 (54h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11721022
telemt_connections_bad_total 1370471
telemt_connections_current 738
telemt_connections_me_current 738
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313744
telemt_upstream_connect_attempt_total 106355
telemt_upstream_connect_success_total 105438
telemt_upstream_connect_fail_total 709
telemt_upstream_connect_attempts_per_request{bucket="1"} 106147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 709
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10760
telemt_me_reconnect_success_total 2670
telemt_me_reader_eof_total 2479
telemt_me_idle_close_by_peer_total 2478
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5661225
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9018938
telemt_me_endpoint_quarantine_total 1612
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1496
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42111
telemt_desync_full_logged_total 13559
telemt_desync_suppressed_total 28552
telemt_desync_frames_bucket_total{bucket="1_2"} 10935
telemt_desync_frames_bucket_total{bucket="3_10"} 15478
telemt_desync_frames_bucket_total{bucket="gt_10"} 15698
telemt_pool_swap_total 208
telemt_pool_force_close_total 5495
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71411
telemt_me_writer_removed_unexpected_total 2514
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67109
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5024
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65916
telemt_me_writer_teardown_success_total{mode="normal"} 74022
telemt_me_writer_teardown_noop_total 71416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.571307
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2137
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9023497
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 157783479544 (146.95 GB)
telemt_user_octets_to_client{user="hello"} 3519779520970 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 85
```