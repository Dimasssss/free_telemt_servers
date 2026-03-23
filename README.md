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

# Server Metrics 2026-03-23 03:07:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 108092.0 (30h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3696463
telemt_connections_bad_total 354508
telemt_connections_current 1071
telemt_connections_me_current 1071
telemt_handshake_timeouts_total 119298
telemt_upstream_connect_attempt_total 40357
telemt_upstream_connect_success_total 40355
telemt_upstream_connect_attempts_per_request{bucket="1"} 40355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1428
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 647
telemt_me_idle_close_by_peer_total 647
telemt_me_route_drop_no_conn_total 3009086
telemt_me_route_drop_channel_closed_total 1237
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3021600
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 761
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 843
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 42
telemt_desync_total 12996
telemt_desync_full_logged_total 4127
telemt_desync_suppressed_total 8869
telemt_desync_frames_bucket_total{bucket="1_2"} 3444
telemt_desync_frames_bucket_total{bucket="3_10"} 4748
telemt_desync_frames_bucket_total{bucket="gt_10"} 4804
telemt_pool_swap_total 119
telemt_pool_force_close_total 3636
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 36908
telemt_me_writer_removed_unexpected_total 624
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2624
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34557
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3580
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33272
telemt_me_writer_teardown_success_total{mode="normal"} 37181
telemt_me_writer_teardown_noop_total 36919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74100
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 379.531353
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74100
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 565
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 3010491
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 42807977004 (39.87 GB)
telemt_user_octets_to_client{user="hello"} 821018940136 (764.63 GB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 121458.1 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4039915
telemt_connections_bad_total 372725
telemt_connections_current 484
telemt_connections_me_current 484
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 101607
telemt_upstream_connect_attempt_total 75377
telemt_upstream_connect_success_total 74462
telemt_upstream_connect_fail_total 808
telemt_upstream_connect_attempts_per_request{bucket="1"} 75270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 808
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10425
telemt_me_reconnect_success_total 3731
telemt_me_reader_eof_total 3716
telemt_me_idle_close_by_peer_total 3716
telemt_me_route_drop_no_conn_total 3646833
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3209988
telemt_me_endpoint_quarantine_total 975
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 953
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
telemt_me_writers_active_current 48
telemt_desync_total 13096
telemt_desync_full_logged_total 7355
telemt_desync_suppressed_total 5741
telemt_desync_frames_bucket_total{bucket="1_2"} 2976
telemt_desync_frames_bucket_total{bucket="3_10"} 5136
telemt_desync_frames_bucket_total{bucket="gt_10"} 4984
telemt_pool_swap_total 114
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 255
telemt_me_draining_writers_reap_progress_total 50455
telemt_me_writer_removed_unexpected_total 3642
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6487
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47255
telemt_me_writer_teardown_success_total{mode="normal"} 54134
telemt_me_writer_teardown_noop_total 50456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.678825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 255
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 3312
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 3223340
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 43353090358 (40.38 GB)
telemt_user_octets_to_client{user="hello"} 800803982310 (745.81 GB)
telemt_user_msgs_from_client{user="hello"} 49767
telemt_user_msgs_to_client{user="hello"} 185105
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 196318.1 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16439777
telemt_connections_bad_total 1668587
telemt_connections_current 1162
telemt_connections_me_current 1162
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 399492
telemt_upstream_connect_attempt_total 88462
telemt_upstream_connect_success_total 88355
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 88372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3057
telemt_me_reconnect_success_total 1630
telemt_me_reader_eof_total 1580
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 14061696
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13050042
telemt_me_endpoint_quarantine_total 1322
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1481
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 54175
telemt_desync_full_logged_total 17263
telemt_desync_suppressed_total 36912
telemt_desync_frames_bucket_total{bucket="1_2"} 12087
telemt_desync_frames_bucket_total{bucket="3_10"} 21164
telemt_desync_frames_bucket_total{bucket="gt_10"} 20924
telemt_pool_swap_total 213
telemt_pool_force_close_total 6877
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1070
telemt_me_draining_writers_reap_progress_total 67556
telemt_me_writer_removed_unexpected_total 1518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60679
telemt_me_writer_teardown_success_total{mode="normal"} 68355
telemt_me_writer_teardown_noop_total 67609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.982477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1070
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1412
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 13050003
telemt_user_connections_current{user="hello"} 1162
telemt_user_octets_from_client{user="hello"} 197953423989 (184.36 GB)
telemt_user_octets_to_client{user="hello"} 3521396089531 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 196319.3 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11979886
telemt_connections_bad_total 1256393
telemt_connections_current 682
telemt_connections_me_current 682
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 345719
telemt_upstream_connect_attempt_total 102717
telemt_upstream_connect_success_total 101379
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 102264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4528
telemt_me_reconnect_success_total 1943
telemt_me_reader_eof_total 1811
telemt_me_idle_close_by_peer_total 1811
telemt_me_route_drop_no_conn_total 4567795
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8877163
telemt_me_endpoint_quarantine_total 1339
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1500
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
telemt_me_writers_active_current 41
telemt_desync_total 39098
telemt_desync_full_logged_total 13165
telemt_desync_suppressed_total 25933
telemt_desync_frames_bucket_total{bucket="1_2"} 9682
telemt_desync_frames_bucket_total{bucket="3_10"} 15017
telemt_desync_frames_bucket_total{bucket="gt_10"} 14399
telemt_pool_swap_total 210
telemt_pool_force_close_total 6228
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 715
telemt_me_draining_writers_reap_progress_total 65652
telemt_me_writer_removed_unexpected_total 1838
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61566
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5716
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59424
telemt_me_writer_teardown_success_total{mode="normal"} 67349
telemt_me_writer_teardown_noop_total 65677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.545620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 715
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 8814877
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 218388959080 (203.39 GB)
telemt_user_octets_to_client{user="hello"} 3982845566683 (3.62 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 196283.3 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11134999
telemt_connections_bad_total 996407
telemt_connections_current 642
telemt_connections_me_current 642
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 346322
telemt_upstream_connect_attempt_total 87129
telemt_upstream_connect_success_total 85564
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 85769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5804
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2169
telemt_me_idle_close_by_peer_total 2168
telemt_me_route_drop_no_conn_total 5346993
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8403356
telemt_me_endpoint_quarantine_total 1379
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1460
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 24
telemt_desync_total 38323
telemt_desync_full_logged_total 12704
telemt_desync_suppressed_total 25619
telemt_desync_frames_bucket_total{bucket="1_2"} 9683
telemt_desync_frames_bucket_total{bucket="3_10"} 14673
telemt_desync_frames_bucket_total{bucket="gt_10"} 13967
telemt_pool_swap_total 205
telemt_pool_force_close_total 6122
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 747
telemt_me_draining_writers_reap_progress_total 66166
telemt_me_writer_removed_unexpected_total 2317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61896
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5551
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60044
telemt_me_writer_teardown_success_total{mode="normal"} 68417
telemt_me_writer_teardown_noop_total 66237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.872738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 747
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2110
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 8395266
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 193108970943 (179.85 GB)
telemt_user_octets_to_client{user="hello"} 3485181024573 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66563.4 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11367813
telemt_connections_bad_total 670839
telemt_connections_current 1155
telemt_connections_me_current 1155
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 288615
telemt_upstream_connect_attempt_total 61573
telemt_upstream_connect_success_total 58394
telemt_upstream_connect_fail_total 2056
telemt_upstream_connect_attempts_per_request{bucket="1"} 60450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2056
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7890
telemt_me_reconnect_success_total 1337
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 25309748
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9425158
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_desync_total 16650
telemt_desync_full_logged_total 4571
telemt_desync_suppressed_total 12079
telemt_desync_frames_bucket_total{bucket="1_2"} 3168
telemt_desync_frames_bucket_total{bucket="3_10"} 6792
telemt_desync_frames_bucket_total{bucket="gt_10"} 6690
telemt_pool_swap_total 68
telemt_pool_force_close_total 2170
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 494
telemt_me_draining_writers_reap_progress_total 21820
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20181
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1849
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 321
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19650
telemt_me_writer_teardown_success_total{mode="normal"} 22992
telemt_me_writer_teardown_noop_total 21839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.026669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 494
telemt_me_refill_failed_total 341
telemt_me_writer_restored_same_endpoint_total 881
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 9450997
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 87908098322 (81.87 GB)
telemt_user_octets_to_client{user="hello"} 636866652458 (593.13 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 196289.9 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11088871
telemt_connections_bad_total 967318
telemt_connections_current 873
telemt_connections_me_current 873
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 244539
telemt_upstream_connect_attempt_total 115947
telemt_upstream_connect_success_total 114759
telemt_upstream_connect_fail_total 1013
telemt_upstream_connect_attempts_per_request{bucket="1"} 115772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1013
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73195
telemt_me_reconnect_success_total 3157
telemt_me_reader_eof_total 2854
telemt_me_idle_close_by_peer_total 2852
telemt_me_route_drop_no_conn_total 5276573
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8738670
telemt_me_endpoint_quarantine_total 1330
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1486
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_warm_current 30
telemt_desync_total 46573
telemt_desync_full_logged_total 15985
telemt_desync_suppressed_total 30588
telemt_desync_frames_bucket_total{bucket="1_2"} 9465
telemt_desync_frames_bucket_total{bucket="3_10"} 17830
telemt_desync_frames_bucket_total{bucket="gt_10"} 19278
telemt_pool_swap_total 201
telemt_pool_force_close_total 5838
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 672
telemt_me_draining_writers_reap_progress_total 70189
telemt_me_writer_removed_unexpected_total 2874
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7059
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5089
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64351
telemt_me_writer_teardown_success_total{mode="normal"} 73107
telemt_me_writer_teardown_noop_total 70190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 142980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.316135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 672
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2660
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 8741537
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 196565751285 (183.07 GB)
telemt_user_octets_to_client{user="hello"} 3340303799380 (3.04 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 133126.1 (36h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11809312
telemt_connections_bad_total 484016
telemt_connections_current 721
telemt_connections_me_current 721
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4786952
telemt_upstream_connect_attempt_total 64609
telemt_upstream_connect_success_total 64142
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 64596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_reconnect_attempts_total 49152
telemt_me_reconnect_success_total 1902
telemt_me_reader_eof_total 1577
telemt_me_idle_close_by_peer_total 1576
telemt_me_route_drop_no_conn_total 4104911
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5672812
telemt_me_endpoint_quarantine_total 909
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1024
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31878
telemt_desync_full_logged_total 10896
telemt_desync_suppressed_total 20982
telemt_desync_frames_bucket_total{bucket="1_2"} 6363
telemt_desync_frames_bucket_total{bucket="3_10"} 12580
telemt_desync_frames_bucket_total{bucket="gt_10"} 12935
telemt_pool_swap_total 141
telemt_pool_force_close_total 4050
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 49785
telemt_me_writer_removed_unexpected_total 1622
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4003
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47453
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3606
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45735
telemt_me_writer_teardown_success_total{mode="normal"} 51456
telemt_me_writer_teardown_noop_total 49792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.735985
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 2745
telemt_me_writer_restored_same_endpoint_total 1681
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5664892
telemt_user_connections_current{user="hello"} 721
telemt_user_octets_from_client{user="hello"} 120409215416 (112.14 GB)
telemt_user_octets_to_client{user="hello"} 2206575668342 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 114097.1 (31h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1575275
telemt_connections_bad_total 36952
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32428
telemt_upstream_connect_attempt_total 54064
telemt_upstream_connect_success_total 53894
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 54035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 805
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 529551
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400283
telemt_me_endpoint_quarantine_total 966
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
telemt_desync_total 9822
telemt_desync_full_logged_total 2780
telemt_desync_suppressed_total 7042
telemt_desync_frames_bucket_total{bucket="1_2"} 3045
telemt_desync_frames_bucket_total{bucket="3_10"} 3711
telemt_desync_frames_bucket_total{bucket="gt_10"} 3066
telemt_pool_swap_total 123
telemt_pool_force_close_total 3099
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 45953
telemt_me_writer_removed_unexpected_total 921
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43431
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42854
telemt_me_writer_teardown_success_total{mode="normal"} 46916
telemt_me_writer_teardown_noop_total 45957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92873
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.449672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92873
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1396018
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 26507518749 (24.69 GB)
telemt_user_octets_to_client{user="hello"} 589404863203 (548.93 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 196294.5 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13411013
telemt_connections_bad_total 1626436
telemt_connections_current 784
telemt_connections_me_current 784
telemt_handshake_timeouts_total 391555
telemt_upstream_connect_attempt_total 78558
telemt_upstream_connect_success_total 78203
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 78422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39473
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3079
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1541
telemt_me_idle_close_by_peer_total 1541
telemt_me_route_drop_no_conn_total 4492551
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10098317
telemt_me_endpoint_quarantine_total 1430
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1486
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
telemt_me_writers_warm_current 39
telemt_desync_total 42351
telemt_desync_full_logged_total 13834
telemt_desync_suppressed_total 28517
telemt_desync_frames_bucket_total{bucket="1_2"} 10300
telemt_desync_frames_bucket_total{bucket="3_10"} 15554
telemt_desync_frames_bucket_total{bucket="gt_10"} 16497
telemt_pool_swap_total 217
telemt_pool_force_close_total 5708
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 71044
telemt_me_writer_removed_unexpected_total 1476
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5513
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65336
telemt_me_writer_teardown_success_total{mode="normal"} 72575
telemt_me_writer_teardown_noop_total 71046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 141001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 142729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 143112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.841859
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1368
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10064955
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 195198119196 (181.79 GB)
telemt_user_octets_to_client{user="hello"} 4476455774888 (4.07 TB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 196291.0 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11716282
telemt_connections_bad_total 1369310
telemt_connections_current 667
telemt_connections_me_current 667
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 313574
telemt_upstream_connect_attempt_total 106171
telemt_upstream_connect_success_total 105254
telemt_upstream_connect_fail_total 709
telemt_upstream_connect_attempts_per_request{bucket="1"} 105963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 709
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10757
telemt_me_reconnect_success_total 2665
telemt_me_reader_eof_total 2475
telemt_me_idle_close_by_peer_total 2474
telemt_me_seq_mismatch_total 103
telemt_me_route_drop_no_conn_total 5660374
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9015632
telemt_me_endpoint_quarantine_total 1607
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1490
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_me_writers_warm_current 25
telemt_desync_total 42107
telemt_desync_full_logged_total 13558
telemt_desync_suppressed_total 28549
telemt_desync_frames_bucket_total{bucket="1_2"} 10932
telemt_desync_frames_bucket_total{bucket="3_10"} 15478
telemt_desync_frames_bucket_total{bucket="gt_10"} 15697
telemt_pool_swap_total 207
telemt_pool_force_close_total 5476
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 71202
telemt_me_writer_removed_unexpected_total 2511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66909
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5005
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65726
telemt_me_writer_teardown_success_total{mode="normal"} 73809
telemt_me_writer_teardown_noop_total 71207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 142324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 144966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.528898
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 419
telemt_me_writer_restored_same_endpoint_total 2134
telemt_me_writer_restored_fallback_total 139
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 9020197
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 157766249404 (146.93 GB)
telemt_user_octets_to_client{user="hello"} 3518593028318 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 87
```