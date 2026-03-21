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

# Server Metrics 2026-03-21 17:00:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 73461.2 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2643830
telemt_connections_bad_total 156897
telemt_connections_current 1484
telemt_connections_me_current 1484
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 81823
telemt_upstream_connect_attempt_total 30785
telemt_upstream_connect_success_total 30653
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 30742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1751
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 2247100
telemt_me_route_drop_channel_closed_total 706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2113906
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 571
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
telemt_desync_total 8408
telemt_desync_full_logged_total 2920
telemt_desync_suppressed_total 5488
telemt_desync_frames_bucket_total{bucket="1_2"} 1821
telemt_desync_frames_bucket_total{bucket="3_10"} 3194
telemt_desync_frames_bucket_total{bucket="gt_10"} 3393
telemt_pool_swap_total 79
telemt_pool_force_close_total 2393
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 545
telemt_me_draining_writers_reap_progress_total 24825
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23129
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22432
telemt_me_writer_teardown_success_total{mode="normal"} 25253
telemt_me_writer_teardown_noop_total 24833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 241.901322
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 545
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 595
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2115058
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 30253669793 (28.18 GB)
telemt_user_octets_to_client{user="hello"} 521305985990 (485.50 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4586.6 (1h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245049
telemt_connections_bad_total 10781
telemt_connections_current 1181
telemt_connections_me_current 1181
telemt_handshake_timeouts_total 6506
telemt_upstream_connect_attempt_total 1862
telemt_upstream_connect_success_total 1860
telemt_upstream_connect_attempts_per_request{bucket="1"} 1860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 21
telemt_me_idle_close_by_peer_total 21
telemt_me_route_drop_no_conn_total 188456
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213578
telemt_me_endpoint_quarantine_total 29
telemt_me_single_endpoint_shadow_rotate_total 43
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 35
telemt_desync_total 836
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 431
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 337
telemt_desync_frames_bucket_total{bucket="gt_10"} 320
telemt_pool_swap_total 4
telemt_pool_force_close_total 75
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 1588
telemt_me_writer_removed_unexpected_total 21
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1513
telemt_me_writer_teardown_success_total{mode="normal"} 1609
telemt_me_writer_teardown_noop_total 1588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.313943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_writer_restored_same_endpoint_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 210537
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 2008157592 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 47045485012 (43.81 GB)
telemt_user_unique_ips_current{user="hello"} 826
telemt_user_unique_ips_recent_window{user="hello"} 321
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 73459.0 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5507618
telemt_connections_bad_total 457890
telemt_connections_current 3223
telemt_connections_me_current 3223
telemt_handshake_timeouts_total 181007
telemt_upstream_connect_attempt_total 26921
telemt_upstream_connect_success_total 26862
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26868
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 608
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 612
telemt_me_route_drop_no_conn_total 3436338
telemt_me_route_drop_channel_closed_total 48
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4539270
telemt_me_endpoint_quarantine_total 460
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 551
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
telemt_desync_total 18415
telemt_desync_full_logged_total 6208
telemt_desync_suppressed_total 12207
telemt_desync_frames_bucket_total{bucket="1_2"} 3900
telemt_desync_frames_bucket_total{bucket="3_10"} 7307
telemt_desync_frames_bucket_total{bucket="gt_10"} 7208
telemt_pool_swap_total 78
telemt_pool_force_close_total 2587
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 409
telemt_me_draining_writers_reap_progress_total 24464
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22610
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21877
telemt_me_writer_teardown_success_total{mode="normal"} 24750
telemt_me_writer_teardown_noop_total 24498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.341502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 409
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 4533835
telemt_user_connections_current{user="hello"} 3223
telemt_user_octets_from_client{user="hello"} 71529514908 (66.62 GB)
telemt_user_octets_to_client{user="hello"} 1430186559348 (1.30 TB)
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 73460.5 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4404104
telemt_connections_bad_total 449320
telemt_connections_current 4032
telemt_connections_me_current 4032
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 149374
telemt_upstream_connect_attempt_total 31244
telemt_upstream_connect_success_total 30955
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 31097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1425
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1471947
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3271302
telemt_me_endpoint_quarantine_total 461
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 560
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
telemt_desync_total 15677
telemt_desync_full_logged_total 5162
telemt_desync_suppressed_total 10515
telemt_desync_frames_bucket_total{bucket="1_2"} 3865
telemt_desync_frames_bucket_total{bucket="3_10"} 6094
telemt_desync_frames_bucket_total{bucket="gt_10"} 5718
telemt_pool_swap_total 80
telemt_pool_force_close_total 2375
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 23564
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22065
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 165
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21189
telemt_me_writer_teardown_success_total{mode="normal"} 24096
telemt_me_writer_teardown_noop_total 23567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47663
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.946398
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47663
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3270251
telemt_user_connections_current{user="hello"} 4032
telemt_user_octets_from_client{user="hello"} 76974090961 (71.69 GB)
telemt_user_octets_to_client{user="hello"} 1494818864363 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1552
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 73424.5 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4346206
telemt_connections_bad_total 430107
telemt_connections_current 3853
telemt_connections_me_current 3853
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129656
telemt_upstream_connect_attempt_total 36486
telemt_upstream_connect_success_total 36241
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 36374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 871
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1509
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 1545608
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3251503
telemt_me_endpoint_quarantine_total 509
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 552
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
telemt_desync_total 15090
telemt_desync_full_logged_total 4947
telemt_desync_suppressed_total 10143
telemt_desync_frames_bucket_total{bucket="1_2"} 3734
telemt_desync_frames_bucket_total{bucket="3_10"} 5696
telemt_desync_frames_bucket_total{bucket="gt_10"} 5660
telemt_pool_swap_total 78
telemt_pool_force_close_total 2274
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 273
telemt_me_draining_writers_reap_progress_total 24928
telemt_me_writer_removed_unexpected_total 595
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23431
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2082
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22654
telemt_me_writer_teardown_success_total{mode="normal"} 25547
telemt_me_writer_teardown_noop_total 24935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.921872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 273
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 3254590
telemt_user_connections_current{user="hello"} 3853
telemt_user_octets_from_client{user="hello"} 80551654849 (75.02 GB)
telemt_user_octets_to_client{user="hello"} 1493664579428 (1.36 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1524
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73463.7 (20h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15097275
telemt_connections_bad_total 969920
telemt_connections_current 5264
telemt_connections_me_current 5264
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 437669
telemt_upstream_connect_attempt_total 147710
telemt_upstream_connect_success_total 131916
telemt_upstream_connect_fail_total 14627
telemt_upstream_connect_attempts_per_request{bucket="1"} 146543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14627
telemt_me_keepalive_timeout_total 262
telemt_me_reconnect_attempts_total 4137
telemt_me_reconnect_success_total 1539
telemt_me_reader_eof_total 1064
telemt_me_idle_close_by_peer_total 1063
telemt_me_route_drop_no_conn_total 29895166
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12441349
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 86
telemt_me_single_endpoint_outage_exit_total 86
telemt_me_single_endpoint_outage_reconnect_attempt_total 195
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 195
telemt_me_single_endpoint_shadow_rotate_total 575
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
telemt_me_writers_active_current 85
telemt_desync_total 21862
telemt_desync_full_logged_total 6726
telemt_desync_suppressed_total 15136
telemt_desync_frames_bucket_total{bucket="1_2"} 4788
telemt_desync_frames_bucket_total{bucket="3_10"} 9541
telemt_desync_frames_bucket_total{bucket="gt_10"} 7533
telemt_pool_swap_total 74
telemt_pool_force_close_total 2439
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 559
telemt_me_draining_writers_reap_progress_total 23207
telemt_me_writer_removed_unexpected_total 1472
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 383
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20768
telemt_me_writer_teardown_success_total{mode="normal"} 24441
telemt_me_writer_teardown_noop_total 23219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47660
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.462386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47660
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 559
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1079
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 12539846
telemt_user_connections_current{user="hello"} 5264
telemt_user_octets_from_client{user="hello"} 101352920586 (94.39 GB)
telemt_user_octets_to_client{user="hello"} 847070177847 (788.90 GB)
telemt_user_msgs_from_client{user="hello"} 290173
telemt_user_msgs_to_client{user="hello"} 585212
telemt_user_unique_ips_current{user="hello"} 2001
telemt_user_unique_ips_recent_window{user="hello"} 977
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 73431.3 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4343671
telemt_connections_bad_total 459399
telemt_connections_current 4423
telemt_connections_me_current 4423
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 92324
telemt_upstream_connect_attempt_total 30483
telemt_upstream_connect_success_total 30102
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 30426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_reconnect_attempts_total 3124
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1084
telemt_me_idle_close_by_peer_total 1084
telemt_me_route_drop_no_conn_total 1854673
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3359978
telemt_me_endpoint_quarantine_total 449
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 546
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
telemt_me_writers_active_current 46
telemt_desync_total 16339
telemt_desync_full_logged_total 5679
telemt_desync_suppressed_total 10660
telemt_desync_frames_bucket_total{bucket="1_2"} 3180
telemt_desync_frames_bucket_total{bucket="3_10"} 6466
telemt_desync_frames_bucket_total{bucket="gt_10"} 6693
telemt_pool_swap_total 73
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 226
telemt_me_draining_writers_reap_progress_total 25574
telemt_me_writer_removed_unexpected_total 1051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1862
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 312
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23400
telemt_me_writer_teardown_success_total{mode="normal"} 26661
telemt_me_writer_teardown_noop_total 25575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.874024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 226
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3342760
telemt_user_connections_current{user="hello"} 4423
telemt_user_octets_from_client{user="hello"} 87141363588 (81.16 GB)
telemt_user_octets_to_client{user="hello"} 1368936844778 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1707
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 10267.0 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1557437
telemt_connections_bad_total 58441
telemt_connections_current 3573
telemt_connections_me_current 3573
telemt_handshake_timeouts_total 712059
telemt_upstream_connect_attempt_total 3441
telemt_upstream_connect_success_total 3380
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 460
telemt_me_reconnect_success_total 117
telemt_me_reader_eof_total 110
telemt_me_idle_close_by_peer_total 110
telemt_me_route_drop_no_conn_total 539729
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 718588
telemt_me_endpoint_quarantine_total 42
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 78
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
telemt_desync_total 3890
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1457
telemt_desync_frames_bucket_total{bucket="gt_10"} 1704
telemt_pool_swap_total 10
telemt_pool_force_close_total 329
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 2943
telemt_me_writer_removed_unexpected_total 112
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2783
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2614
telemt_me_writer_teardown_success_total{mode="normal"} 3055
telemt_me_writer_teardown_noop_total 2943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.249258
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 717423
telemt_user_connections_current{user="hello"} 3573
telemt_user_octets_from_client{user="hello"} 16932776984 (15.77 GB)
telemt_user_octets_to_client{user="hello"} 273551357584 (254.76 GB)
telemt_user_unique_ips_current{user="hello"} 1409
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71417.3 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1409029
telemt_connections_bad_total 155024
telemt_connections_current 2446
telemt_connections_me_current 2446
telemt_handshake_timeouts_total 494461
telemt_upstream_connect_attempt_total 32854
telemt_upstream_connect_success_total 32843
telemt_upstream_connect_attempts_per_request{bucket="1"} 32843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1374
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 582
telemt_me_idle_close_by_peer_total 582
telemt_me_route_drop_no_conn_total 315469
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675436
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 594
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
telemt_desync_total 3965
telemt_desync_full_logged_total 1419
telemt_desync_suppressed_total 2546
telemt_desync_frames_bucket_total{bucket="1_2"} 762
telemt_desync_frames_bucket_total{bucket="3_10"} 1413
telemt_desync_frames_bucket_total{bucket="gt_10"} 1790
telemt_pool_swap_total 78
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 29431
telemt_me_writer_removed_unexpected_total 549
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27754
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1828
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27571
telemt_me_writer_teardown_success_total{mode="normal"} 29999
telemt_me_writer_teardown_noop_total 29431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.387492
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 674905
telemt_user_connections_current{user="hello"} 2446
telemt_user_octets_from_client{user="hello"} 14043693267 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 258734760665 (240.97 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 995
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 73435.6 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4877449
telemt_connections_bad_total 447474
telemt_connections_current 4612
telemt_connections_me_current 4612
telemt_handshake_timeouts_total 158840
telemt_upstream_connect_attempt_total 28789
telemt_upstream_connect_success_total 28670
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 28753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14462
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 1233
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 613
telemt_me_idle_close_by_peer_total 613
telemt_me_route_drop_no_conn_total 1484458
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3848141
telemt_me_endpoint_quarantine_total 519
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 563
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
telemt_me_writers_active_current 43
telemt_desync_total 14946
telemt_desync_full_logged_total 4955
telemt_desync_suppressed_total 9991
telemt_desync_frames_bucket_total{bucket="1_2"} 3542
telemt_desync_frames_bucket_total{bucket="3_10"} 5541
telemt_desync_frames_bucket_total{bucket="gt_10"} 5863
telemt_pool_swap_total 81
telemt_pool_force_close_total 2152
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 25815
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24333
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23663
telemt_me_writer_teardown_success_total{mode="normal"} 26418
telemt_me_writer_teardown_noop_total 25816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.405118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52234
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3838371
telemt_user_connections_current{user="hello"} 4612
telemt_user_octets_from_client{user="hello"} 76066564280 (70.84 GB)
telemt_user_octets_to_client{user="hello"} 1793016931072 (1.63 TB)
telemt_user_unique_ips_current{user="hello"} 1667
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 73432.4 (20h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4285770
telemt_connections_bad_total 388454
telemt_connections_current 4198
telemt_connections_me_current 4198
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 131178
telemt_upstream_connect_attempt_total 45251
telemt_upstream_connect_success_total 44928
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 45195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 605
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_reconnect_attempts_total 4133
telemt_me_reconnect_success_total 916
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1567196
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3413619
telemt_me_endpoint_quarantine_total 608
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 556
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
telemt_desync_total 13354
telemt_desync_full_logged_total 4546
telemt_desync_suppressed_total 8808
telemt_desync_frames_bucket_total{bucket="1_2"} 3317
telemt_desync_frames_bucket_total{bucket="3_10"} 4962
telemt_desync_frames_bucket_total{bucket="gt_10"} 5075
telemt_pool_swap_total 79
telemt_pool_force_close_total 2095
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 25145
telemt_me_writer_removed_unexpected_total 809
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2493
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23050
telemt_me_writer_teardown_success_total{mode="normal"} 25987
telemt_me_writer_teardown_noop_total 25147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.201180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 183
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 3421313
telemt_user_connections_current{user="hello"} 4198
telemt_user_octets_from_client{user="hello"} 62128200333 (57.86 GB)
telemt_user_octets_to_client{user="hello"} 1443669344768 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 607
```