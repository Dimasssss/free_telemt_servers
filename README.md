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

# Server Metrics 2026-03-22 13:04:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 57468.9 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1765041
telemt_connections_bad_total 80067
telemt_connections_current 1918
telemt_connections_me_current 1918
telemt_handshake_timeouts_total 77015
telemt_upstream_connect_attempt_total 21639
telemt_upstream_connect_success_total 21638
telemt_upstream_connect_attempts_per_request{bucket="1"} 21638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14105
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 352
telemt_me_reader_eof_total 356
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 1239498
telemt_me_route_drop_channel_closed_total 546
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1497794
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 398
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 455
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
telemt_me_writers_active_current 46
telemt_desync_total 8575
telemt_desync_full_logged_total 2608
telemt_desync_suppressed_total 5967
telemt_desync_frames_bucket_total{bucket="1_2"} 2404
telemt_desync_frames_bucket_total{bucket="3_10"} 3229
telemt_desync_frames_bucket_total{bucket="gt_10"} 2942
telemt_pool_swap_total 63
telemt_pool_force_close_total 1884
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 301
telemt_me_draining_writers_reap_progress_total 19712
telemt_me_writer_removed_unexpected_total 347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1397
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17828
telemt_me_writer_teardown_success_total{mode="normal"} 19935
telemt_me_writer_teardown_noop_total 19714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39649
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 145.912999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39649
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 301
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1494939
telemt_user_connections_current{user="hello"} 1918
telemt_user_octets_from_client{user="hello"} 23454974456 (21.84 GB)
telemt_user_octets_to_client{user="hello"} 438371668912 (408.27 GB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 352
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 70835.2 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2843751
telemt_connections_bad_total 269488
telemt_connections_current 2019
telemt_connections_me_current 2019
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 67559
telemt_upstream_connect_attempt_total 46133
telemt_upstream_connect_success_total 45593
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 46071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3531
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1473
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 2548450
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2227295
telemt_me_endpoint_quarantine_total 596
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 553
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 8812
telemt_desync_full_logged_total 4940
telemt_desync_suppressed_total 3872
telemt_desync_frames_bucket_total{bucket="1_2"} 2067
telemt_desync_frames_bucket_total{bucket="3_10"} 3434
telemt_desync_frames_bucket_total{bucket="gt_10"} 3311
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 28130
telemt_me_writer_removed_unexpected_total 1433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26488
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26124
telemt_me_writer_teardown_success_total{mode="normal"} 29563
telemt_me_writer_teardown_noop_total 28130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.320518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1326
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2238962
telemt_user_connections_current{user="hello"} 2019
telemt_user_octets_from_client{user="hello"} 27463170383 (25.58 GB)
telemt_user_octets_to_client{user="hello"} 532013267586 (495.48 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 890
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 145695.0 (40h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13293336
telemt_connections_bad_total 1176729
telemt_connections_current 6041
telemt_connections_me_current 6041
telemt_handshake_timeouts_total 341798
telemt_upstream_connect_attempt_total 53002
telemt_upstream_connect_success_total 52922
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1267
telemt_me_reader_eof_total 1210
telemt_me_idle_close_by_peer_total 1209
telemt_me_route_drop_no_conn_total 11099605
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10630631
telemt_me_endpoint_quarantine_total 925
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1084
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
telemt_me_writers_active_current 51
telemt_desync_total 43755
telemt_desync_full_logged_total 13936
telemt_desync_suppressed_total 29819
telemt_desync_frames_bucket_total{bucket="1_2"} 9904
telemt_desync_frames_bucket_total{bucket="3_10"} 17103
telemt_desync_frames_bucket_total{bucket="gt_10"} 16748
telemt_pool_swap_total 156
telemt_pool_force_close_total 5333
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 845
telemt_me_draining_writers_reap_progress_total 48327
telemt_me_writer_removed_unexpected_total 1167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 429
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42994
telemt_me_writer_teardown_success_total{mode="normal"} 48839
telemt_me_writer_teardown_noop_total 48375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 242.091001
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97214
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 845
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1092
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 10618788
telemt_user_connections_current{user="hello"} 6041
telemt_user_octets_from_client{user="hello"} 156119787964 (145.40 GB)
telemt_user_octets_to_client{user="hello"} 2911943394940 (2.65 TB)
telemt_user_unique_ips_current{user="hello"} 2261
telemt_user_unique_ips_recent_window{user="hello"} 989
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 145696.6 (40h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9981017
telemt_connections_bad_total 922704
telemt_connections_current 5368
telemt_connections_me_current 5368
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 300500
telemt_upstream_connect_attempt_total 79421
telemt_upstream_connect_success_total 78289
telemt_upstream_connect_fail_total 815
telemt_upstream_connect_attempts_per_request{bucket="1"} 79104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3675
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 815
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3465
telemt_me_reconnect_success_total 1418
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1303
telemt_me_route_drop_no_conn_total 3991656
telemt_me_route_drop_channel_closed_total 415
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7447027
telemt_me_endpoint_quarantine_total 907
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1105
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
telemt_me_writers_active_current 43
telemt_desync_total 33575
telemt_desync_full_logged_total 11319
telemt_desync_suppressed_total 22256
telemt_desync_frames_bucket_total{bucket="1_2"} 8288
telemt_desync_frames_bucket_total{bucket="3_10"} 12914
telemt_desync_frames_bucket_total{bucket="gt_10"} 12373
telemt_pool_swap_total 155
telemt_pool_force_close_total 4760
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 46623
telemt_me_writer_removed_unexpected_total 1335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43629
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 405
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41863
telemt_me_writer_teardown_success_total{mode="normal"} 47826
telemt_me_writer_teardown_noop_total 46635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 85.012656
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 1215
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7387134
telemt_user_connections_current{user="hello"} 5368
telemt_user_octets_from_client{user="hello"} 190549274213 (177.46 GB)
telemt_user_octets_to_client{user="hello"} 3351001156378 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2079
telemt_user_unique_ips_recent_window{user="hello"} 738
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 145660.7 (40h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9401917
telemt_connections_bad_total 795998
telemt_connections_current 4091
telemt_connections_me_current 4091
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 298724
telemt_upstream_connect_attempt_total 64565
telemt_upstream_connect_success_total 63810
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3892
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1514
telemt_me_idle_close_by_peer_total 1513
telemt_me_route_drop_no_conn_total 4068700
telemt_me_route_drop_channel_closed_total 295
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7085256
telemt_me_endpoint_quarantine_total 999
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1067
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 33451
telemt_desync_full_logged_total 11094
telemt_desync_suppressed_total 22357
telemt_desync_frames_bucket_total{bucket="1_2"} 8504
telemt_desync_frames_bucket_total{bucket="3_10"} 12801
telemt_desync_frames_bucket_total{bucket="gt_10"} 12146
telemt_pool_swap_total 152
telemt_pool_force_close_total 4730
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 614
telemt_me_draining_writers_reap_progress_total 47262
telemt_me_writer_removed_unexpected_total 1594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4580
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42532
telemt_me_writer_teardown_success_total{mode="normal"} 48778
telemt_me_writer_teardown_noop_total 47329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3096.364401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 614
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1472
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 7076729
telemt_user_connections_current{user="hello"} 4091
telemt_user_octets_from_client{user="hello"} 170023284733 (158.35 GB)
telemt_user_octets_to_client{user="hello"} 3023323946281 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1659
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 15940.7 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6711385
telemt_connections_bad_total 416989
telemt_connections_current 7082
telemt_connections_me_current 7082
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 105892
telemt_upstream_connect_attempt_total 24872
telemt_upstream_connect_success_total 23751
telemt_upstream_connect_fail_total 844
telemt_upstream_connect_attempts_per_request{bucket="1"} 24595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4644
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 844
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 2394
telemt_me_reconnect_success_total 416
telemt_me_reader_eof_total 282
telemt_me_idle_close_by_peer_total 282
telemt_me_route_drop_no_conn_total 16165171
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5598767
telemt_me_endpoint_quarantine_total 97
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 129
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
telemt_me_writers_active_current 85
telemt_desync_total 8353
telemt_desync_full_logged_total 2141
telemt_desync_suppressed_total 6212
telemt_desync_frames_bucket_total{bucket="1_2"} 1511
telemt_desync_frames_bucket_total{bucket="3_10"} 3368
telemt_desync_frames_bucket_total{bucket="gt_10"} 3474
telemt_pool_swap_total 14
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 4172
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3602
telemt_me_writer_teardown_success_total{mode="normal"} 4501
telemt_me_writer_teardown_noop_total 4175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.860796
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 295
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 5612039
telemt_user_connections_current{user="hello"} 7082
telemt_user_octets_from_client{user="hello"} 30598572778 (28.50 GB)
telemt_user_octets_to_client{user="hello"} 166305772227 (154.88 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2597
telemt_user_unique_ips_recent_window{user="hello"} 1515
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 145667.3 (40h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9182512
telemt_connections_bad_total 767162
telemt_connections_current 5058
telemt_connections_me_current 5058
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 197738
telemt_upstream_connect_attempt_total 89071
telemt_upstream_connect_success_total 88195
telemt_upstream_connect_fail_total 754
telemt_upstream_connect_attempts_per_request{bucket="1"} 88949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 754
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71173
telemt_me_reconnect_success_total 2374
telemt_me_reader_eof_total 2117
telemt_me_idle_close_by_peer_total 2116
telemt_me_route_drop_no_conn_total 4431503
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7257739
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1088
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 37158
telemt_desync_full_logged_total 12731
telemt_desync_suppressed_total 24427
telemt_desync_frames_bucket_total{bucket="1_2"} 7558
telemt_desync_frames_bucket_total{bucket="3_10"} 14313
telemt_desync_frames_bucket_total{bucket="gt_10"} 15287
telemt_pool_swap_total 149
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 532
telemt_me_draining_writers_reap_progress_total 49839
telemt_me_writer_removed_unexpected_total 2145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5254
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46746
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3798
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 597
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45444
telemt_me_writer_teardown_success_total{mode="normal"} 52000
telemt_me_writer_teardown_noop_total 49840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.230884
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 532
telemt_me_refill_failed_total 4247
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 7259753
telemt_user_connections_current{user="hello"} 5058
telemt_user_octets_from_client{user="hello"} 169292430835 (157.67 GB)
telemt_user_octets_to_client{user="hello"} 2781840182545 (2.53 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1971
telemt_user_unique_ips_recent_window{user="hello"} 689
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 82503.4 (22h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8901640
telemt_connections_bad_total 316779
telemt_connections_current 5187
telemt_connections_me_current 5187
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3735631
telemt_upstream_connect_attempt_total 41388
telemt_upstream_connect_success_total 41092
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 41381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_reconnect_attempts_total 47893
telemt_me_reconnect_success_total 1424
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 3140828
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4310597
telemt_me_endpoint_quarantine_total 549
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 621
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 23710
telemt_desync_full_logged_total 7940
telemt_desync_suppressed_total 15770
telemt_desync_frames_bucket_total{bucket="1_2"} 4820
telemt_desync_frames_bucket_total{bucket="3_10"} 9296
telemt_desync_frames_bucket_total{bucket="gt_10"} 9594
telemt_pool_swap_total 86
telemt_pool_force_close_total 2671
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 274
telemt_me_draining_writers_reap_progress_total 28850
telemt_me_writer_removed_unexpected_total 1157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2617
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27418
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26179
telemt_me_writer_teardown_success_total{mode="normal"} 30035
telemt_me_writer_teardown_noop_total 28857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58892
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.261866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58892
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 274
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1272
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4305772
telemt_user_connections_current{user="hello"} 5187
telemt_user_octets_from_client{user="hello"} 95460118612 (88.90 GB)
telemt_user_octets_to_client{user="hello"} 1674170628318 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1958
telemt_user_unique_ips_recent_window{user="hello"} 907
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63473.8 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726010
telemt_connections_bad_total 8507
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13903
telemt_upstream_connect_attempt_total 32430
telemt_upstream_connect_success_total 32348
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1450
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 243937
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655597
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_desync_total 3580
telemt_desync_full_logged_total 1057
telemt_desync_suppressed_total 2523
telemt_desync_frames_bucket_total{bucket="1_2"} 877
telemt_desync_frames_bucket_total{bucket="3_10"} 1423
telemt_desync_frames_bucket_total{bucket="gt_10"} 1280
telemt_pool_swap_total 67
telemt_pool_force_close_total 1654
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 26586
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2028
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25160
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24932
telemt_me_writer_teardown_success_total{mode="normal"} 27188
telemt_me_writer_teardown_noop_total 26588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.922979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 657276
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 12517799053 (11.66 GB)
telemt_user_octets_to_client{user="hello"} 314598564815 (292.99 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 145671.6 (40h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11205670
telemt_connections_bad_total 1301213
telemt_connections_current 5891
telemt_connections_me_current 5891
telemt_handshake_timeouts_total 301164
telemt_upstream_connect_attempt_total 55150
telemt_upstream_connect_success_total 54937
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 55102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 1150
telemt_me_reader_eof_total 1114
telemt_me_idle_close_by_peer_total 1114
telemt_me_route_drop_no_conn_total 3527735
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8419575
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1093
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
telemt_me_writers_active_current 43
telemt_desync_total 34361
telemt_desync_full_logged_total 11262
telemt_desync_suppressed_total 23099
telemt_desync_frames_bucket_total{bucket="1_2"} 8235
telemt_desync_frames_bucket_total{bucket="3_10"} 12705
telemt_desync_frames_bucket_total{bucket="gt_10"} 13421
telemt_pool_swap_total 161
telemt_pool_force_close_total 4414
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 49695
telemt_me_writer_removed_unexpected_total 1069
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4059
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 150
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45281
telemt_me_writer_teardown_success_total{mode="normal"} 50800
telemt_me_writer_teardown_noop_total 49697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.950788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 1006
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8390484
telemt_user_connections_current{user="hello"} 5891
telemt_user_octets_from_client{user="hello"} 161391089412 (150.31 GB)
telemt_user_octets_to_client{user="hello"} 3790167413668 (3.45 TB)
telemt_user_unique_ips_current{user="hello"} 2246
telemt_user_unique_ips_recent_window{user="hello"} 789
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 145668.4 (40h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9703155
telemt_connections_bad_total 1090251
telemt_connections_current 4532
telemt_connections_me_current 4532
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 252333
telemt_upstream_connect_attempt_total 80466
telemt_upstream_connect_success_total 79881
telemt_upstream_connect_fail_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 80388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1996
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 507
telemt_me_reconnect_attempts_total 8500
telemt_me_reconnect_success_total 1871
telemt_me_reader_eof_total 1742
telemt_me_idle_close_by_peer_total 1742
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4224204
telemt_me_route_drop_channel_closed_total 303
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7465383
telemt_me_endpoint_quarantine_total 1115
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1098
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
telemt_desync_total 33605
telemt_desync_full_logged_total 10989
telemt_desync_suppressed_total 22616
telemt_desync_frames_bucket_total{bucket="1_2"} 8307
telemt_desync_frames_bucket_total{bucket="3_10"} 12519
telemt_desync_frames_bucket_total{bucket="gt_10"} 12779
telemt_pool_swap_total 155
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 539
telemt_me_draining_writers_reap_progress_total 48820
telemt_me_writer_removed_unexpected_total 1767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5028
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45625
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3921
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44536
telemt_me_writer_teardown_success_total{mode="normal"} 50653
telemt_me_writer_teardown_noop_total 48824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.804849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 539
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1514
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 7472752
telemt_user_connections_current{user="hello"} 4532
telemt_user_octets_from_client{user="hello"} 132639369117 (123.53 GB)
telemt_user_octets_to_client{user="hello"} 2968991524023 (2.70 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1838
telemt_user_unique_ips_recent_window{user="hello"} 681
```