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

# Server Metrics 2026-03-21 20:03:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 84434.9 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3033689
telemt_connections_bad_total 176892
telemt_connections_current 1040
telemt_connections_me_current 1040
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 92955
telemt_upstream_connect_attempt_total 34546
telemt_upstream_connect_success_total 34403
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 34503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1864
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 2611070
telemt_me_route_drop_channel_closed_total 838
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2453558
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 658
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
telemt_me_writers_active_current 44
telemt_desync_total 9766
telemt_desync_full_logged_total 3413
telemt_desync_suppressed_total 6353
telemt_desync_frames_bucket_total{bucket="1_2"} 2131
telemt_desync_frames_bucket_total{bucket="3_10"} 3697
telemt_desync_frames_bucket_total{bucket="gt_10"} 3938
telemt_pool_swap_total 91
telemt_pool_force_close_total 2761
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 637
telemt_me_draining_writers_reap_progress_total 28263
telemt_me_writer_removed_unexpected_total 703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2381
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25502
telemt_me_writer_teardown_success_total{mode="normal"} 28706
telemt_me_writer_teardown_noop_total 28271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 296.838447
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 637
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2453249
telemt_user_connections_current{user="hello"} 1040
telemt_user_octets_from_client{user="hello"} 36331389181 (33.84 GB)
telemt_user_octets_to_client{user="hello"} 618450471290 (575.98 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 9572.3 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396413
telemt_connections_bad_total 18423
telemt_connections_current 1190
telemt_connections_me_current 1190
telemt_handshake_timeouts_total 13837
telemt_upstream_connect_attempt_total 3826
telemt_upstream_connect_success_total 3743
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 3815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 172
telemt_me_reconnect_success_total 126
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 102
telemt_me_route_drop_no_conn_total 251262
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 325823
telemt_me_endpoint_quarantine_total 77
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 77
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
telemt_me_writers_active_current 44
telemt_desync_total 1418
telemt_desync_full_logged_total 795
telemt_desync_suppressed_total 623
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 10
telemt_pool_force_close_total 309
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3309
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 289
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3109
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3000
telemt_me_writer_teardown_success_total{mode="normal"} 3398
telemt_me_writer_teardown_noop_total 3309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6707
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.408222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6707
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 86
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 325453
telemt_user_connections_current{user="hello"} 1190
telemt_user_octets_from_client{user="hello"} 5237325872 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 92257148688 (85.92 GB)
telemt_user_unique_ips_current{user="hello"} 783
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 84432.1 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6705720
telemt_connections_bad_total 515643
telemt_connections_current 3445
telemt_connections_me_current 3445
telemt_handshake_timeouts_total 210853
telemt_upstream_connect_attempt_total 30355
telemt_upstream_connect_success_total 30293
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16533
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1280
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 666
telemt_me_idle_close_by_peer_total 666
telemt_me_route_drop_no_conn_total 4300740
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5511677
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 626
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
telemt_me_writers_active_current 44
telemt_desync_total 22533
telemt_desync_full_logged_total 7500
telemt_desync_suppressed_total 15033
telemt_desync_frames_bucket_total{bucket="1_2"} 4725
telemt_desync_frames_bucket_total{bucket="3_10"} 8973
telemt_desync_frames_bucket_total{bucket="gt_10"} 8835
telemt_pool_swap_total 90
telemt_pool_force_close_total 3016
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 27621
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2385
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25527
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2786
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24605
telemt_me_writer_teardown_success_total{mode="normal"} 27912
telemt_me_writer_teardown_noop_total 27658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55570
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 131.030715
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55570
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5505046
telemt_user_connections_current{user="hello"} 3445
telemt_user_octets_from_client{user="hello"} 91939724368 (85.63 GB)
telemt_user_octets_to_client{user="hello"} 1715647225828 (1.56 TB)
telemt_user_unique_ips_current{user="hello"} 1521
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 84434.3 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5415025
telemt_connections_bad_total 515461
telemt_connections_current 3634
telemt_connections_me_current 3634
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 179336
telemt_upstream_connect_attempt_total 34521
telemt_upstream_connect_success_total 34206
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 34367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1646
telemt_me_reconnect_success_total 689
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 1874024
telemt_me_route_drop_channel_closed_total 215
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4056120
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_me_writers_active_current 45
telemt_desync_total 19115
telemt_desync_full_logged_total 6339
telemt_desync_suppressed_total 12776
telemt_desync_frames_bucket_total{bucket="1_2"} 4652
telemt_desync_frames_bucket_total{bucket="3_10"} 7403
telemt_desync_frames_bucket_total{bucket="gt_10"} 7060
telemt_pool_swap_total 92
telemt_pool_force_close_total 2789
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 26464
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24725
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23675
telemt_me_writer_teardown_success_total{mode="normal"} 27033
telemt_me_writer_teardown_noop_total 26469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.600797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 589
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4053207
telemt_user_connections_current{user="hello"} 3634
telemt_user_octets_from_client{user="hello"} 120556513077 (112.28 GB)
telemt_user_octets_to_client{user="hello"} 1840654935475 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1391
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 84397.4 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5345921
telemt_connections_bad_total 483216
telemt_connections_current 3611
telemt_connections_me_current 3611
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 161740
telemt_upstream_connect_attempt_total 40915
telemt_upstream_connect_success_total 40651
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1705
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 685
telemt_me_idle_close_by_peer_total 685
telemt_me_route_drop_no_conn_total 1935109
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4038719
telemt_me_endpoint_quarantine_total 569
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 629
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
telemt_desync_total 18786
telemt_desync_full_logged_total 6127
telemt_desync_suppressed_total 12659
telemt_desync_frames_bucket_total{bucket="1_2"} 4644
telemt_desync_frames_bucket_total{bucket="3_10"} 7127
telemt_desync_frames_bucket_total{bucket="gt_10"} 7015
telemt_pool_swap_total 90
telemt_pool_force_close_total 2653
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 328
telemt_me_draining_writers_reap_progress_total 27897
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26192
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2443
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25244
telemt_me_writer_teardown_success_total{mode="normal"} 28572
telemt_me_writer_teardown_noop_total 27907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.670208
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 328
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 637
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 4041208
telemt_user_connections_current{user="hello"} 3611
telemt_user_octets_from_client{user="hello"} 118305088275 (110.18 GB)
telemt_user_octets_to_client{user="hello"} 1839930404655 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1429
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 84436.5 (23h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18605180
telemt_connections_bad_total 1178432
telemt_connections_current 4583
telemt_connections_me_current 4583
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 521210
telemt_upstream_connect_attempt_total 173973
telemt_upstream_connect_success_total 157114
telemt_upstream_connect_fail_total 15493
telemt_upstream_connect_attempts_per_request{bucket="1"} 172607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8819
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15493
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4598
telemt_me_reconnect_success_total 1724
telemt_me_reader_eof_total 1181
telemt_me_idle_close_by_peer_total 1180
telemt_me_route_drop_no_conn_total 38042081
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15325235
telemt_me_endpoint_quarantine_total 618
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 653
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
telemt_desync_total 28383
telemt_desync_full_logged_total 8384
telemt_desync_suppressed_total 19999
telemt_desync_frames_bucket_total{bucket="1_2"} 6092
telemt_desync_frames_bucket_total{bucket="3_10"} 12657
telemt_desync_frames_bucket_total{bucket="gt_10"} 9634
telemt_pool_swap_total 86
telemt_pool_force_close_total 2858
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 641
telemt_me_draining_writers_reap_progress_total 26021
telemt_me_writer_removed_unexpected_total 1633
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23941
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23163
telemt_me_writer_teardown_success_total{mode="normal"} 27412
telemt_me_writer_teardown_noop_total 26037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 198.513675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 641
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 15444192
telemt_user_connections_current{user="hello"} 4582
telemt_user_octets_from_client{user="hello"} 140861054119 (131.19 GB)
telemt_user_octets_to_client{user="hello"} 946735847115 (881.72 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1711
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 84404.2 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5277479
telemt_connections_bad_total 511478
telemt_connections_current 3597
telemt_connections_me_current 3597
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 108608
telemt_upstream_connect_attempt_total 43973
telemt_upstream_connect_success_total 43514
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 43892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_reconnect_attempts_total 3459
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 2220847
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4089841
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 626
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
telemt_me_writers_active_current 46
telemt_desync_total 20196
telemt_desync_full_logged_total 7012
telemt_desync_suppressed_total 13184
telemt_desync_frames_bucket_total{bucket="1_2"} 3875
telemt_desync_frames_bucket_total{bucket="3_10"} 7913
telemt_desync_frames_bucket_total{bucket="gt_10"} 8408
telemt_pool_swap_total 85
telemt_pool_force_close_total 2499
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 28670
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2155
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26171
telemt_me_writer_teardown_success_total{mode="normal"} 29828
telemt_me_writer_teardown_noop_total 28671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58499
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.738694
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58499
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 4080305
telemt_user_connections_current{user="hello"} 3597
telemt_user_octets_from_client{user="hello"} 108770068165 (101.30 GB)
telemt_user_octets_to_client{user="hello"} 1646248157995 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1464
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 21239.9 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2894863
telemt_connections_bad_total 108908
telemt_connections_current 2980
telemt_connections_me_current 2980
telemt_handshake_timeouts_total 1244131
telemt_upstream_connect_attempt_total 6812
telemt_upstream_connect_success_total 6715
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 6806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 668
telemt_me_reconnect_success_total 201
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 865897
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1369448
telemt_me_endpoint_quarantine_total 102
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 157
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
telemt_me_writers_active_current 45
telemt_desync_total 7489
telemt_desync_full_logged_total 2456
telemt_desync_suppressed_total 5033
telemt_desync_frames_bucket_total{bucket="1_2"} 1334
telemt_desync_frames_bucket_total{bucket="3_10"} 2812
telemt_desync_frames_bucket_total{bucket="gt_10"} 3343
telemt_pool_swap_total 22
telemt_pool_force_close_total 710
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 5931
telemt_me_writer_removed_unexpected_total 183
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5560
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5221
telemt_me_writer_teardown_success_total{mode="normal"} 6119
telemt_me_writer_teardown_noop_total 5931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.954469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 166
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 1365827
telemt_user_connections_current{user="hello"} 2980
telemt_user_octets_from_client{user="hello"} 42198717468 (39.30 GB)
telemt_user_octets_to_client{user="hello"} 553945638724 (515.90 GB)
telemt_user_unique_ips_current{user="hello"} 1279
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 2211.0 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22550
telemt_connections_bad_total 36
telemt_connections_current 729
telemt_connections_me_current 729
telemt_handshake_timeouts_total 520
telemt_upstream_connect_attempt_total 968
telemt_upstream_connect_success_total 966
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 6268
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20789
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_shadow_rotate_total 23
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
telemt_me_writers_active_current 46
telemt_desync_total 95
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 806
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 763
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 748
telemt_me_writer_teardown_success_total{mode="normal"} 817
telemt_me_writer_teardown_noop_total 806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.047667
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 20760
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 763963196 (728.57 MB)
telemt_user_octets_to_client{user="hello"} 16589925668 (15.45 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 84409.0 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6225767
telemt_connections_bad_total 629382
telemt_connections_current 4144
telemt_connections_me_current 4144
telemt_handshake_timeouts_total 182216
telemt_upstream_connect_attempt_total 32154
telemt_upstream_connect_success_total 32025
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 32117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 1358
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 1936773
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4790396
telemt_me_endpoint_quarantine_total 565
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_desync_total 18100
telemt_desync_full_logged_total 5984
telemt_desync_suppressed_total 12116
telemt_desync_frames_bucket_total{bucket="1_2"} 4431
telemt_desync_frames_bucket_total{bucket="3_10"} 6614
telemt_desync_frames_bucket_total{bucket="gt_10"} 7055
telemt_pool_swap_total 93
telemt_pool_force_close_total 2527
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 316
telemt_me_draining_writers_reap_progress_total 28851
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2456
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26324
telemt_me_writer_teardown_success_total{mode="normal"} 29510
telemt_me_writer_teardown_noop_total 28852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.392598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 316
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 622
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4766607
telemt_user_connections_current{user="hello"} 4144
telemt_user_octets_from_client{user="hello"} 94921682168 (88.40 GB)
telemt_user_octets_to_client{user="hello"} 2210168401140 (2.01 TB)
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 488
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 84405.3 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5266313
telemt_connections_bad_total 487958
telemt_connections_current 3992
telemt_connections_me_current 3992
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 152882
telemt_upstream_connect_attempt_total 48516
telemt_upstream_connect_success_total 48159
telemt_upstream_connect_fail_total 298
telemt_upstream_connect_attempts_per_request{bucket="1"} 48457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17981
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 298
telemt_me_reconnect_attempts_total 4435
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 866
telemt_me_idle_close_by_peer_total 866
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 1990216
telemt_me_route_drop_channel_closed_total 180
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4170458
telemt_me_endpoint_quarantine_total 670
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 642
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
telemt_me_writers_active_current 45
telemt_desync_total 16661
telemt_desync_full_logged_total 5655
telemt_desync_suppressed_total 11006
telemt_desync_frames_bucket_total{bucket="1_2"} 4117
telemt_desync_frames_bucket_total{bucket="3_10"} 6132
telemt_desync_frames_bucket_total{bucket="gt_10"} 6412
telemt_pool_swap_total 91
telemt_pool_force_close_total 2462
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 28060
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2270
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25598
telemt_me_writer_teardown_success_total{mode="normal"} 28976
telemt_me_writer_teardown_noop_total 28062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57038
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.265214
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57038
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 755
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4175370
telemt_user_connections_current{user="hello"} 3992
telemt_user_octets_from_client{user="hello"} 78483373533 (73.09 GB)
telemt_user_octets_to_client{user="hello"} 1741756822068 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1532
telemt_user_unique_ips_recent_window{user="hello"} 471
```