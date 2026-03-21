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

# Server Metrics 2026-03-21 16:50:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 72852.1 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2618052
telemt_connections_bad_total 155625
telemt_connections_current 1418
telemt_connections_me_current 1418
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81479
telemt_upstream_connect_attempt_total 30572
telemt_upstream_connect_success_total 30440
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17766
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 2221239
telemt_me_route_drop_channel_closed_total 695
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2090886
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 499
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 564
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
telemt_me_writers_active_current 44
telemt_desync_total 8328
telemt_desync_full_logged_total 2886
telemt_desync_suppressed_total 5442
telemt_desync_frames_bucket_total{bucket="1_2"} 1811
telemt_desync_frames_bucket_total{bucket="3_10"} 3163
telemt_desync_frames_bucket_total{bucket="gt_10"} 3354
telemt_pool_swap_total 78
telemt_pool_force_close_total 2363
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 24630
telemt_me_writer_removed_unexpected_total 642
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2111
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22945
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22267
telemt_me_writer_teardown_success_total{mode="normal"} 25056
telemt_me_writer_teardown_noop_total 24637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 235.683791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2092073
telemt_user_connections_current{user="hello"} 1418
telemt_user_octets_from_client{user="hello"} 29799793757 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 516092865746 (480.65 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3977.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230102
telemt_connections_bad_total 10278
telemt_connections_current 930
telemt_connections_me_current 930
telemt_handshake_timeouts_total 5890
telemt_upstream_connect_attempt_total 1634
telemt_upstream_connect_success_total 1632
telemt_upstream_connect_attempts_per_request{bucket="1"} 1632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 183567
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201164
telemt_me_endpoint_quarantine_total 29
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 804
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 4
telemt_pool_force_close_total 75
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 1421
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1321
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1346
telemt_me_writer_teardown_success_total{mode="normal"} 1437
telemt_me_writer_teardown_noop_total 1421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.310326
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_writer_restored_same_endpoint_total 15
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 198140
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 1872897716 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 42186797340 (39.29 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 72849.4 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5458092
telemt_connections_bad_total 456491
telemt_connections_current 4891
telemt_connections_me_current 4891
telemt_handshake_timeouts_total 180359
telemt_upstream_connect_attempt_total 26699
telemt_upstream_connect_success_total 26640
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14549
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1181
telemt_me_reconnect_success_total 601
telemt_me_reader_eof_total 605
telemt_me_idle_close_by_peer_total 605
telemt_me_route_drop_no_conn_total 3410707
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4497314
telemt_me_endpoint_quarantine_total 454
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 543
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
telemt_desync_total 18248
telemt_desync_full_logged_total 6143
telemt_desync_suppressed_total 12105
telemt_desync_frames_bucket_total{bucket="1_2"} 3867
telemt_desync_frames_bucket_total{bucket="3_10"} 7238
telemt_desync_frames_bucket_total{bucket="gt_10"} 7143
telemt_pool_swap_total 77
telemt_pool_force_close_total 2557
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 407
telemt_me_draining_writers_reap_progress_total 24273
telemt_me_writer_removed_unexpected_total 585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2348
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21716
telemt_me_writer_teardown_success_total{mode="normal"} 24552
telemt_me_writer_teardown_noop_total 24307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48859
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.381820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48859
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 407
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4491958
telemt_user_connections_current{user="hello"} 4891
telemt_user_octets_from_client{user="hello"} 70536577688 (65.69 GB)
telemt_user_octets_to_client{user="hello"} 1416278011988 (1.29 TB)
telemt_user_unique_ips_current{user="hello"} 1961
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 72851.2 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4349448
telemt_connections_bad_total 446495
telemt_connections_current 4089
telemt_connections_me_current 4089
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 148429
telemt_upstream_connect_attempt_total 31046
telemt_upstream_connect_success_total 30758
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1421
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 588
telemt_me_idle_close_by_peer_total 588
telemt_me_route_drop_no_conn_total 1420874
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3225162
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 554
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 15452
telemt_desync_full_logged_total 5091
telemt_desync_suppressed_total 10361
telemt_desync_frames_bucket_total{bucket="1_2"} 3811
telemt_desync_frames_bucket_total{bucket="3_10"} 5999
telemt_desync_frames_bucket_total{bucket="gt_10"} 5642
telemt_pool_swap_total 79
telemt_pool_force_close_total 2321
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 23363
telemt_me_writer_removed_unexpected_total 569
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 162
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21042
telemt_me_writer_teardown_success_total{mode="normal"} 23912
telemt_me_writer_teardown_noop_total 23366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.453701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3224264
telemt_user_connections_current{user="hello"} 4089
telemt_user_octets_from_client{user="hello"} 74931240785 (69.79 GB)
telemt_user_octets_to_client{user="hello"} 1476152392219 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1597
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 72815.1 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4290900
telemt_connections_bad_total 427388
telemt_connections_current 3747
telemt_connections_me_current 3747
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128670
telemt_upstream_connect_attempt_total 36284
telemt_upstream_connect_success_total 36040
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 870
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1505
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 622
telemt_me_idle_close_by_peer_total 622
telemt_me_route_drop_no_conn_total 1528780
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3204791
telemt_me_endpoint_quarantine_total 508
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 545
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
telemt_me_writers_active_current 41
telemt_desync_total 14966
telemt_desync_full_logged_total 4893
telemt_desync_suppressed_total 10073
telemt_desync_frames_bucket_total{bucket="1_2"} 3691
telemt_desync_frames_bucket_total{bucket="3_10"} 5656
telemt_desync_frames_bucket_total{bucket="gt_10"} 5619
telemt_pool_swap_total 77
telemt_pool_force_close_total 2242
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 24754
telemt_me_writer_removed_unexpected_total 591
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2052
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22512
telemt_me_writer_teardown_success_total{mode="normal"} 25368
telemt_me_writer_teardown_noop_total 24761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.181855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3207959
telemt_user_connections_current{user="hello"} 3747
telemt_user_octets_from_client{user="hello"} 79167746725 (73.73 GB)
telemt_user_octets_to_client{user="hello"} 1473158058768 (1.34 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1509
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 72854.3 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14895384
telemt_connections_bad_total 958344
telemt_connections_current 5700
telemt_connections_me_current 5700
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 433444
telemt_upstream_connect_attempt_total 147369
telemt_upstream_connect_success_total 131611
telemt_upstream_connect_fail_total 14621
telemt_upstream_connect_attempts_per_request{bucket="1"} 146232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14621
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4078
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 1010
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 29536538
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12272926
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 571
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
telemt_me_writers_active_current 45
telemt_desync_total 21563
telemt_desync_full_logged_total 6647
telemt_desync_suppressed_total 14916
telemt_desync_frames_bucket_total{bucket="1_2"} 4723
telemt_desync_frames_bucket_total{bucket="3_10"} 9398
telemt_desync_frames_bucket_total{bucket="gt_10"} 7442
telemt_pool_swap_total 74
telemt_pool_force_close_total 2439
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 552
telemt_me_draining_writers_reap_progress_total 23038
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21175
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20599
telemt_me_writer_teardown_success_total{mode="normal"} 24213
telemt_me_writer_teardown_noop_total 23050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47263
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.362539
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47263
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 552
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1024
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 12371432
telemt_user_connections_current{user="hello"} 5700
telemt_user_octets_from_client{user="hello"} 100710910406 (93.79 GB)
telemt_user_octets_to_client{user="hello"} 840126516995 (782.43 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 1992
telemt_user_unique_ips_recent_window{user="hello"} 998
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 72821.9 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4289048
telemt_connections_bad_total 452826
telemt_connections_current 4210
telemt_connections_me_current 4210
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 91162
telemt_upstream_connect_attempt_total 30237
telemt_upstream_connect_success_total 29873
telemt_upstream_connect_fail_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 30189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 316
telemt_me_reconnect_attempts_total 3109
telemt_me_reconnect_success_total 1082
telemt_me_reader_eof_total 1070
telemt_me_idle_close_by_peer_total 1070
telemt_me_route_drop_no_conn_total 1835870
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3317622
telemt_me_endpoint_quarantine_total 442
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 539
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
telemt_me_writers_active_current 49
telemt_desync_total 16120
telemt_desync_full_logged_total 5595
telemt_desync_suppressed_total 10525
telemt_desync_frames_bucket_total{bucket="1_2"} 3142
telemt_desync_frames_bucket_total{bucket="3_10"} 6386
telemt_desync_frames_bucket_total{bucket="gt_10"} 6592
telemt_pool_swap_total 72
telemt_pool_force_close_total 2139
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 25399
telemt_me_writer_removed_unexpected_total 1037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23260
telemt_me_writer_teardown_success_total{mode="normal"} 26472
telemt_me_writer_teardown_noop_total 25400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.711501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 933
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 3300515
telemt_user_connections_current{user="hello"} 4210
telemt_user_octets_from_client{user="hello"} 86137685408 (80.22 GB)
telemt_user_octets_to_client{user="hello"} 1352841934810 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1748
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 9657.6 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466898
telemt_connections_bad_total 51657
telemt_connections_current 3653
telemt_connections_me_current 3653
telemt_handshake_timeouts_total 672090
telemt_upstream_connect_attempt_total 3228
telemt_upstream_connect_success_total 3172
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 3222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 111
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 523007
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680245
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 72
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
telemt_me_writers_active_current 44
telemt_desync_total 3665
telemt_desync_full_logged_total 1161
telemt_desync_suppressed_total 2504
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1353
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 9
telemt_pool_force_close_total 296
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 2749
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2608
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2453
telemt_me_writer_teardown_success_total{mode="normal"} 2854
telemt_me_writer_teardown_noop_total 2749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.845136
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 679229
telemt_user_connections_current{user="hello"} 3653
telemt_user_octets_from_client{user="hello"} 16152797608 (15.04 GB)
telemt_user_octets_to_client{user="hello"} 257902957432 (240.19 GB)
telemt_user_unique_ips_current{user="hello"} 1442
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70808.0 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1358088
telemt_connections_bad_total 149852
telemt_connections_current 1220
telemt_connections_me_current 1220
telemt_handshake_timeouts_total 480458
telemt_upstream_connect_attempt_total 32625
telemt_upstream_connect_success_total 32616
telemt_upstream_connect_attempts_per_request{bucket="1"} 32616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 301242
telemt_me_route_drop_channel_closed_total 30
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646702
telemt_me_endpoint_quarantine_total 620
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 589
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3851
telemt_desync_full_logged_total 1380
telemt_desync_suppressed_total 2471
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 1374
telemt_desync_frames_bucket_total{bucket="gt_10"} 1740
telemt_pool_swap_total 77
telemt_pool_force_close_total 1828
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 29220
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2224
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27563
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27392
telemt_me_writer_teardown_success_total{mode="normal"} 29787
telemt_me_writer_teardown_noop_total 29220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.802111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 646242
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 13293982127 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 248806190297 (231.72 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 72826.4 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4807452
telemt_connections_bad_total 444449
telemt_connections_current 4939
telemt_connections_me_current 4939
telemt_handshake_timeouts_total 157701
telemt_upstream_connect_attempt_total 28567
telemt_upstream_connect_success_total 28449
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1212
telemt_me_reconnect_success_total 639
telemt_me_reader_eof_total 608
telemt_me_idle_close_by_peer_total 608
telemt_me_route_drop_no_conn_total 1468556
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3796539
telemt_me_endpoint_quarantine_total 514
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 556
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
telemt_me_writers_active_current 47
telemt_desync_total 14798
telemt_desync_full_logged_total 4900
telemt_desync_suppressed_total 9898
telemt_desync_frames_bucket_total{bucket="1_2"} 3500
telemt_desync_frames_bucket_total{bucket="3_10"} 5497
telemt_desync_frames_bucket_total{bucket="gt_10"} 5801
telemt_pool_swap_total 80
telemt_pool_force_close_total 2122
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 250
telemt_me_draining_writers_reap_progress_total 25617
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2061
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24154
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23495
telemt_me_writer_teardown_success_total{mode="normal"} 26215
telemt_me_writer_teardown_noop_total 25618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.388720
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 250
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 568
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3786841
telemt_user_connections_current{user="hello"} 4939
telemt_user_octets_from_client{user="hello"} 75229531556 (70.06 GB)
telemt_user_octets_to_client{user="hello"} 1770477660640 (1.61 TB)
telemt_user_unique_ips_current{user="hello"} 1732
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 72823.0 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4224947
telemt_connections_bad_total 381114
telemt_connections_current 3936
telemt_connections_me_current 3936
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 130416
telemt_upstream_connect_attempt_total 45031
telemt_upstream_connect_success_total 44713
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 44975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 603
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_reconnect_attempts_total 4125
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 789
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1546679
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3368790
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 549
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
telemt_me_writers_active_current 43
telemt_desync_total 13205
telemt_desync_full_logged_total 4481
telemt_desync_suppressed_total 8724
telemt_desync_frames_bucket_total{bucket="1_2"} 3291
telemt_desync_frames_bucket_total{bucket="3_10"} 4908
telemt_desync_frames_bucket_total{bucket="gt_10"} 5006
telemt_pool_swap_total 78
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 237
telemt_me_draining_writers_reap_progress_total 24958
telemt_me_writer_removed_unexpected_total 802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2461
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23332
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 175
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22891
telemt_me_writer_teardown_success_total{mode="normal"} 25793
telemt_me_writer_teardown_noop_total 24959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.044695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 237
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3376541
telemt_user_connections_current{user="hello"} 3936
telemt_user_octets_from_client{user="hello"} 61182968821 (56.98 GB)
telemt_user_octets_to_client{user="hello"} 1427860064404 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1612
telemt_user_unique_ips_recent_window{user="hello"} 557
```