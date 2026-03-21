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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 14:11:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63358.2 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2165206
telemt_connections_bad_total 105313
telemt_connections_current 1823
telemt_connections_me_current 1823
telemt_handshake_timeouts_total 74615
telemt_upstream_connect_attempt_total 24299
telemt_upstream_connect_success_total 24175
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 24256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1438
telemt_me_reconnect_success_total 607
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 1815442
telemt_me_route_drop_channel_closed_total 555
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1725566
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 89
telemt_desync_total 6808
telemt_desync_full_logged_total 2324
telemt_desync_suppressed_total 4484
telemt_desync_frames_bucket_total{bucket="1_2"} 1524
telemt_desync_frames_bucket_total{bucket="3_10"} 2597
telemt_desync_frames_bucket_total{bucket="gt_10"} 2687
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 428
telemt_me_draining_writers_reap_progress_total 21690
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19630
telemt_me_writer_teardown_success_total{mode="normal"} 22045
telemt_me_writer_teardown_noop_total 21696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43741
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 189.386102
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43741
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 428
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1724264
telemt_user_connections_current{user="hello"} 1823
telemt_user_octets_from_client{user="hello"} 25101806171 (23.38 GB)
telemt_user_octets_to_client{user="hello"} 433224611903 (403.47 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 355
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2911.8 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254222
telemt_connections_bad_total 9048
telemt_connections_current 3129
telemt_connections_me_current 3129
telemt_handshake_timeouts_total 7462
telemt_upstream_connect_attempt_total 1181
telemt_upstream_connect_success_total 1179
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 20
telemt_me_reader_eof_total 18
telemt_me_idle_close_by_peer_total 18
telemt_me_route_drop_no_conn_total 152340
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224575
telemt_me_endpoint_quarantine_total 24
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 29
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
telemt_desync_total 890
telemt_desync_full_logged_total 356
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 3
telemt_pool_force_close_total 80
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 807
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 764
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 727
telemt_me_writer_teardown_success_total{mode="normal"} 825
telemt_me_writer_teardown_noop_total 807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.304768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 221513
telemt_user_connections_current{user="hello"} 3129
telemt_user_octets_from_client{user="hello"} 4147328743 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 53108984779 (49.46 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1513
telemt_user_unique_ips_recent_window{user="hello"} 611
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 63356.0 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4267949
telemt_connections_bad_total 401174
telemt_connections_current 3712
telemt_connections_me_current 3712
telemt_handshake_timeouts_total 161852
telemt_upstream_connect_attempt_total 23969
telemt_upstream_connect_success_total 23927
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 952
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 547
telemt_me_idle_close_by_peer_total 547
telemt_me_route_drop_no_conn_total 2309274
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3463170
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_me_writers_active_current 43
telemt_desync_total 14401
telemt_desync_full_logged_total 4869
telemt_desync_suppressed_total 9532
telemt_desync_frames_bucket_total{bucket="1_2"} 3057
telemt_desync_frames_bucket_total{bucket="3_10"} 5672
telemt_desync_frames_bucket_total{bucket="gt_10"} 5672
telemt_pool_swap_total 67
telemt_pool_force_close_total 2162
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 337
telemt_me_draining_writers_reap_progress_total 21762
telemt_me_writer_removed_unexpected_total 528
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1898
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1974
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19600
telemt_me_writer_teardown_success_total{mode="normal"} 22081
telemt_me_writer_teardown_noop_total 21791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.230142
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 337
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 498
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 3458826
telemt_user_connections_current{user="hello"} 3712
telemt_user_octets_from_client{user="hello"} 56655945084 (52.76 GB)
telemt_user_octets_to_client{user="hello"} 1170515698172 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 1370
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 63357.3 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3482231
telemt_connections_bad_total 387174
telemt_connections_current 4028
telemt_connections_me_current 4028
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 128736
telemt_upstream_connect_attempt_total 28262
telemt_upstream_connect_success_total 27984
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1183
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 518
telemt_me_idle_close_by_peer_total 518
telemt_me_route_drop_no_conn_total 1086617
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2525536
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
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
telemt_me_writers_active_current 43
telemt_desync_total 11558
telemt_desync_full_logged_total 3914
telemt_desync_suppressed_total 7644
telemt_desync_frames_bucket_total{bucket="1_2"} 2894
telemt_desync_frames_bucket_total{bucket="3_10"} 4462
telemt_desync_frames_bucket_total{bucket="gt_10"} 4202
telemt_pool_swap_total 69
telemt_pool_force_close_total 1975
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 182
telemt_me_draining_writers_reap_progress_total 20897
telemt_me_writer_removed_unexpected_total 502
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1768
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19638
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18922
telemt_me_writer_teardown_success_total{mode="normal"} 21406
telemt_me_writer_teardown_noop_total 20898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.131146
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 182
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2525786
telemt_user_connections_current{user="hello"} 4028
telemt_user_octets_from_client{user="hello"} 47008913437 (43.78 GB)
telemt_user_octets_to_client{user="hello"} 1181064173115 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1490
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 63321.5 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3384276
telemt_connections_bad_total 360106
telemt_connections_current 3423
telemt_connections_me_current 3423
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 99220
telemt_upstream_connect_attempt_total 33458
telemt_upstream_connect_success_total 33227
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 847
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 570
telemt_me_route_drop_no_conn_total 1039721
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2482463
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 476
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
telemt_me_writers_active_current 46
telemt_desync_total 11586
telemt_desync_full_logged_total 3855
telemt_desync_suppressed_total 7731
telemt_desync_frames_bucket_total{bucket="1_2"} 2931
telemt_desync_frames_bucket_total{bucket="3_10"} 4362
telemt_desync_frames_bucket_total{bucket="gt_10"} 4293
telemt_pool_swap_total 67
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 22241
telemt_me_writer_removed_unexpected_total 543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1877
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1736
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20333
telemt_me_writer_teardown_success_total{mode="normal"} 22819
telemt_me_writer_teardown_noop_total 22246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45065
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.602397
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45065
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2487013
telemt_user_connections_current{user="hello"} 3423
telemt_user_octets_from_client{user="hello"} 53789959613 (50.10 GB)
telemt_user_octets_to_client{user="hello"} 1173415343868 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1309
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 63360.8 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11608243
telemt_connections_bad_total 774179
telemt_connections_current 5479
telemt_connections_me_current 5479
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 361457
telemt_upstream_connect_attempt_total 112738
telemt_upstream_connect_success_total 103042
telemt_upstream_connect_fail_total 8713
telemt_upstream_connect_attempts_per_request{bucket="1"} 111755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8713
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3704
telemt_me_reconnect_success_total 1314
telemt_me_reader_eof_total 945
telemt_me_idle_close_by_peer_total 944
telemt_me_route_drop_no_conn_total 21558982
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9510385
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 69
telemt_me_single_endpoint_outage_exit_total 69
telemt_me_single_endpoint_outage_reconnect_attempt_total 154
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 154
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_me_writers_active_current 50
telemt_desync_total 17415
telemt_desync_full_logged_total 5532
telemt_desync_suppressed_total 11883
telemt_desync_frames_bucket_total{bucket="1_2"} 3794
telemt_desync_frames_bucket_total{bucket="3_10"} 7614
telemt_desync_frames_bucket_total{bucket="gt_10"} 6007
telemt_pool_swap_total 64
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 20573
telemt_me_writer_removed_unexpected_total 1256
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18946
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18506
telemt_me_writer_teardown_success_total{mode="normal"} 21650
telemt_me_writer_teardown_noop_total 20583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.884520
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 930
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 9585079
telemt_user_connections_current{user="hello"} 5479
telemt_user_octets_from_client{user="hello"} 70511758227 (65.67 GB)
telemt_user_octets_to_client{user="hello"} 751234096539 (699.64 GB)
telemt_user_msgs_from_client{user="hello"} 228562
telemt_user_msgs_to_client{user="hello"} 540142
telemt_user_unique_ips_current{user="hello"} 1940
telemt_user_unique_ips_recent_window{user="hello"} 948
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 63328.3 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3406536
telemt_connections_bad_total 383734
telemt_connections_current 4080
telemt_connections_me_current 4080
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 74721
telemt_upstream_connect_attempt_total 27158
telemt_upstream_connect_success_total 26866
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 27124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 2643
telemt_me_reconnect_success_total 958
telemt_me_reader_eof_total 951
telemt_me_idle_close_by_peer_total 951
telemt_me_route_drop_no_conn_total 1362024
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2611459
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 479
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 12383
telemt_desync_full_logged_total 4305
telemt_desync_suppressed_total 8078
telemt_desync_frames_bucket_total{bucket="1_2"} 2384
telemt_desync_frames_bucket_total{bucket="3_10"} 4945
telemt_desync_frames_bucket_total{bucket="gt_10"} 5054
telemt_pool_swap_total 63
telemt_pool_force_close_total 1827
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 22752
telemt_me_writer_removed_unexpected_total 922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2238
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20925
telemt_me_writer_teardown_success_total{mode="normal"} 23704
telemt_me_writer_teardown_noop_total 22753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.127882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 2595447
telemt_user_connections_current{user="hello"} 4080
telemt_user_octets_from_client{user="hello"} 55626251892 (51.81 GB)
telemt_user_octets_to_client{user="hello"} 1114432454498 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1550
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 164.2 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32434
telemt_connections_bad_total 445
telemt_connections_current 2949
telemt_connections_me_current 2949
telemt_handshake_timeouts_total 15049
telemt_upstream_connect_attempt_total 138
telemt_upstream_connect_success_total 131
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 4
telemt_me_route_drop_no_conn_total 3335
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12335
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 7
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 38
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_draining_writers_reap_progress_total 44
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44
telemt_me_writer_teardown_success_total{mode="normal"} 44
telemt_me_writer_teardown_noop_total 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88
telemt_user_connections_total{user="hello"} 12334
telemt_user_connections_current{user="hello"} 2949
telemt_user_octets_from_client{user="hello"} 189536856 (180.76 MB)
telemt_user_octets_to_client{user="hello"} 3536686048 (3.29 GB)
telemt_user_unique_ips_current{user="hello"} 1136
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61314.0 (17h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1114173
telemt_connections_bad_total 135569
telemt_connections_current 813
telemt_connections_me_current 813
telemt_handshake_timeouts_total 393982
telemt_upstream_connect_attempt_total 28732
telemt_upstream_connect_success_total 28729
telemt_upstream_connect_attempts_per_request{bucket="1"} 28729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1222
telemt_me_reconnect_success_total 474
telemt_me_reader_eof_total 472
telemt_me_idle_close_by_peer_total 472
telemt_me_route_drop_no_conn_total 235931
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513549
telemt_me_endpoint_quarantine_total 562
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 515
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
telemt_me_writers_active_current 43
telemt_desync_total 3318
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2091
telemt_desync_frames_bucket_total{bucket="1_2"} 592
telemt_desync_frames_bucket_total{bucket="3_10"} 1186
telemt_desync_frames_bucket_total{bucket="gt_10"} 1540
telemt_pool_swap_total 68
telemt_pool_force_close_total 1527
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 25726
telemt_me_writer_removed_unexpected_total 445
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24301
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24199
telemt_me_writer_teardown_success_total{mode="normal"} 26183
telemt_me_writer_teardown_noop_total 25726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51909
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.420503
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51909
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 385
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 513313
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 10538583615 (9.81 GB)
telemt_user_octets_to_client{user="hello"} 193268546769 (180.00 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 63332.6 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3721299
telemt_connections_bad_total 346760
telemt_connections_current 5148
telemt_connections_me_current 5148
telemt_handshake_timeouts_total 115356
telemt_upstream_connect_attempt_total 25679
telemt_upstream_connect_success_total 25575
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1048
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 546
telemt_me_idle_close_by_peer_total 546
telemt_me_route_drop_no_conn_total 1099639
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2948727
telemt_me_endpoint_quarantine_total 471
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 488
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
telemt_me_writers_active_current 42
telemt_desync_total 11710
telemt_desync_full_logged_total 3871
telemt_desync_suppressed_total 7839
telemt_desync_frames_bucket_total{bucket="1_2"} 2787
telemt_desync_frames_bucket_total{bucket="3_10"} 4353
telemt_desync_frames_bucket_total{bucket="gt_10"} 4570
telemt_pool_swap_total 70
telemt_pool_force_close_total 1820
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 23070
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21790
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21250
telemt_me_writer_teardown_success_total{mode="normal"} 23605
telemt_me_writer_teardown_noop_total 23070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.272838
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 516
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 2940910
telemt_user_connections_current{user="hello"} 5148
telemt_user_octets_from_client{user="hello"} 61723940248 (57.48 GB)
telemt_user_octets_to_client{user="hello"} 1388502109460 (1.26 TB)
telemt_user_unique_ips_current{user="hello"} 1688
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 63329.4 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3349132
telemt_connections_bad_total 294231
telemt_connections_current 3668
telemt_connections_me_current 3668
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 97657
telemt_upstream_connect_attempt_total 41881
telemt_upstream_connect_success_total 41605
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 41834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 590
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_reconnect_attempts_total 3579
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1192670
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2690919
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 487
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 10348
telemt_desync_full_logged_total 3528
telemt_desync_suppressed_total 6820
telemt_desync_frames_bucket_total{bucket="1_2"} 2620
telemt_desync_frames_bucket_total{bucket="3_10"} 3828
telemt_desync_frames_bucket_total{bucket="gt_10"} 3900
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22227
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2129
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20807
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20458
telemt_me_writer_teardown_success_total{mode="normal"} 22936
telemt_me_writer_teardown_noop_total 22228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.455473
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2699851
telemt_user_connections_current{user="hello"} 3668
telemt_user_octets_from_client{user="hello"} 48725266497 (45.38 GB)
telemt_user_octets_to_client{user="hello"} 1160509785316 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1367
telemt_user_unique_ips_recent_window{user="hello"} 519
```