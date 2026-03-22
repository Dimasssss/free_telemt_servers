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

# Server Metrics 2026-03-22 08:48:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42153.5 (11h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013758
telemt_connections_bad_total 57884
telemt_connections_current 1812
telemt_connections_me_current 1812
telemt_handshake_timeouts_total 46660
telemt_upstream_connect_attempt_total 16690
telemt_upstream_connect_success_total 16689
telemt_upstream_connect_attempts_per_request{bucket="1"} 16689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 482
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 254
telemt_me_idle_close_by_peer_total 254
telemt_me_route_drop_no_conn_total 560590
telemt_me_route_drop_channel_closed_total 183
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 843580
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_shadow_rotate_total 338
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 6268
telemt_desync_full_logged_total 1761
telemt_desync_suppressed_total 4507
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 2348
telemt_desync_frames_bucket_total{bucket="gt_10"} 2020
telemt_pool_swap_total 46
telemt_pool_force_close_total 1297
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 15170
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1049
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13873
telemt_me_writer_teardown_success_total{mode="normal"} 15372
telemt_me_writer_teardown_noop_total 15172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.510311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 842030
telemt_user_connections_current{user="hello"} 1812
telemt_user_octets_from_client{user="hello"} 12296538540 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 270749717492 (252.16 GB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 55519.3 (15h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532611
telemt_connections_bad_total 151373
telemt_connections_current 1573
telemt_connections_me_current 1573
telemt_handshake_timeouts_total 43050
telemt_upstream_connect_attempt_total 28939
telemt_upstream_connect_success_total 28513
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 28887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2481
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 714969
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1157509
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 440
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
telemt_me_writers_active_current 42
telemt_desync_total 5127
telemt_desync_full_logged_total 2967
telemt_desync_suppressed_total 2160
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 1991
telemt_desync_frames_bucket_total{bucket="gt_10"} 2021
telemt_pool_swap_total 57
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 22668
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21372
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21087
telemt_me_writer_teardown_success_total{mode="normal"} 23592
telemt_me_writer_teardown_noop_total 22668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46260
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.109827
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46260
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 1159058
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 17786594562 (16.57 GB)
telemt_user_octets_to_client{user="hello"} 395706476991 (368.53 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 998
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 130380.0 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9839425
telemt_connections_bad_total 879709
telemt_connections_current 5094
telemt_connections_me_current 5094
telemt_handshake_timeouts_total 293269
telemt_upstream_connect_attempt_total 48040
telemt_upstream_connect_success_total 47960
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1915
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 5582647
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7727631
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 977
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 33554
telemt_desync_full_logged_total 11017
telemt_desync_suppressed_total 22537
telemt_desync_frames_bucket_total{bucket="1_2"} 7377
telemt_desync_frames_bucket_total{bucket="3_10"} 13046
telemt_desync_frames_bucket_total{bucket="gt_10"} 13131
telemt_pool_swap_total 140
telemt_pool_force_close_total 4681
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 43856
telemt_me_writer_removed_unexpected_total 959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 314
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39175
telemt_me_writer_teardown_success_total{mode="normal"} 44271
telemt_me_writer_teardown_noop_total 43900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88171
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 188.120746
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88171
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 7717779
telemt_user_connections_current{user="hello"} 5094
telemt_user_octets_from_client{user="hello"} 126806146656 (118.10 GB)
telemt_user_octets_to_client{user="hello"} 2563315254528 (2.33 TB)
telemt_user_unique_ips_current{user="hello"} 1990
telemt_user_unique_ips_recent_window{user="hello"} 736
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 130380.6 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8019172
telemt_connections_bad_total 718241
telemt_connections_current 4256
telemt_connections_me_current 4256
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 257258
telemt_upstream_connect_attempt_total 54038
telemt_upstream_connect_success_total 53560
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 53806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2898
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 2682411
telemt_me_route_drop_channel_closed_total 320
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5925682
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1005
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
telemt_me_writers_active_current 44
telemt_desync_total 27182
telemt_desync_full_logged_total 9255
telemt_desync_suppressed_total 17927
telemt_desync_frames_bucket_total{bucket="1_2"} 6564
telemt_desync_frames_bucket_total{bucket="3_10"} 10512
telemt_desync_frames_bucket_total{bucket="gt_10"} 10106
telemt_pool_swap_total 142
telemt_pool_force_close_total 4267
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 458
telemt_me_draining_writers_reap_progress_total 42058
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37791
telemt_me_writer_teardown_success_total{mode="normal"} 42978
telemt_me_writer_teardown_noop_total 42064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85042
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.006361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85042
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 458
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5848245
telemt_user_connections_current{user="hello"} 4256
telemt_user_octets_from_client{user="hello"} 161557227551 (150.46 GB)
telemt_user_octets_to_client{user="hello"} 2809875578922 (2.56 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1659
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 130344.7 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7702847
telemt_connections_bad_total 638297
telemt_connections_current 3917
telemt_connections_me_current 3917
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 255553
telemt_upstream_connect_attempt_total 58451
telemt_upstream_connect_success_total 57771
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2844
telemt_me_reconnect_success_total 1222
telemt_me_reader_eof_total 1122
telemt_me_idle_close_by_peer_total 1122
telemt_me_route_drop_no_conn_total 3100645
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5745500
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 960
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
telemt_me_writers_active_current 42
telemt_desync_total 26985
telemt_desync_full_logged_total 9186
telemt_desync_suppressed_total 17799
telemt_desync_frames_bucket_total{bucket="1_2"} 6519
telemt_desync_frames_bucket_total{bucket="3_10"} 10358
telemt_desync_frames_bucket_total{bucket="gt_10"} 10108
telemt_pool_swap_total 139
telemt_pool_force_close_total 4146
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 43025
telemt_me_writer_removed_unexpected_total 1133
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3828
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38879
telemt_me_writer_teardown_success_total{mode="normal"} 44142
telemt_me_writer_teardown_noop_total 43037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.895979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1059
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 5738522
telemt_user_connections_current{user="hello"} 3917
telemt_user_octets_from_client{user="hello"} 148481430623 (138.28 GB)
telemt_user_octets_to_client{user="hello"} 2544512501131 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1575
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 624.6 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230600
telemt_connections_bad_total 24208
telemt_connections_current 5663
telemt_connections_me_current 5663
telemt_handshake_timeouts_total 2375
telemt_upstream_connect_attempt_total 220
telemt_upstream_connect_success_total 199
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 98
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 89
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 401724
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184327
telemt_me_endpoint_quarantine_total 2
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 49
telemt_desync_total 303
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_force_close_total 2
telemt_me_draining_writers_reap_progress_total 104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 102
telemt_me_writer_teardown_success_total{mode="normal"} 104
telemt_me_writer_teardown_noop_total 104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 208
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.027029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 208
telemt_user_connections_total{user="hello"} 184326
telemt_user_connections_current{user="hello"} 5663
telemt_user_octets_from_client{user="hello"} 945150540 (901.37 MB)
telemt_user_octets_to_client{user="hello"} 6950673384 (6.47 GB)
telemt_user_unique_ips_current{user="hello"} 2105
telemt_user_unique_ips_recent_window{user="hello"} 1180
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 130351.8 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7343616
telemt_connections_bad_total 663541
telemt_connections_current 4096
telemt_connections_me_current 4096
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 150595
telemt_upstream_connect_attempt_total 74709
telemt_upstream_connect_success_total 73914
telemt_upstream_connect_fail_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 74591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 441
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 677
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70325
telemt_me_reconnect_success_total 2004
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1760
telemt_me_route_drop_no_conn_total 2878343
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5762951
telemt_me_endpoint_quarantine_total 878
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 985
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 29101
telemt_desync_full_logged_total 10117
telemt_desync_suppressed_total 18984
telemt_desync_frames_bucket_total{bucket="1_2"} 5804
telemt_desync_frames_bucket_total{bucket="3_10"} 11203
telemt_desync_frames_bucket_total{bucket="gt_10"} 12094
telemt_pool_swap_total 136
telemt_pool_force_close_total 3897
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 45211
telemt_me_writer_removed_unexpected_total 1791
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4568
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41314
telemt_me_writer_teardown_success_total{mode="normal"} 47028
telemt_me_writer_teardown_noop_total 45212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.366357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 4228
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 5761219
telemt_user_connections_current{user="hello"} 4096
telemt_user_octets_from_client{user="hello"} 146192771715 (136.15 GB)
telemt_user_octets_to_client{user="hello"} 2380454151759 (2.17 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1724
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 67187.7 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5802312
telemt_connections_bad_total 229868
telemt_connections_current 4228
telemt_connections_me_current 4228
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2303476
telemt_upstream_connect_attempt_total 36026
telemt_upstream_connect_success_total 35772
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 36019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_reconnect_attempts_total 47372
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 1452109
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2910941
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 513
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15812
telemt_desync_full_logged_total 5366
telemt_desync_suppressed_total 10446
telemt_desync_frames_bucket_total{bucket="1_2"} 3100
telemt_desync_frames_bucket_total{bucket="3_10"} 6087
telemt_desync_frames_bucket_total{bucket="gt_10"} 6625
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24164
telemt_me_writer_removed_unexpected_total 920
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22004
telemt_me_writer_teardown_success_total{mode="normal"} 25106
telemt_me_writer_teardown_noop_total 24170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.613983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2911911
telemt_user_connections_current{user="hello"} 4228
telemt_user_octets_from_client{user="hello"} 74268424800 (69.17 GB)
telemt_user_octets_to_client{user="hello"} 1271509488038 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1637
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48158.2 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427524
telemt_connections_bad_total 2913
telemt_connections_current 880
telemt_connections_me_current 880
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8482
telemt_upstream_connect_attempt_total 25723
telemt_upstream_connect_success_total 25663
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 25718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1013
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 135599
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385838
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 1768
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1248
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 52
telemt_pool_force_close_total 1194
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 20706
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1461
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19628
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19512
telemt_me_writer_teardown_success_total{mode="normal"} 21089
telemt_me_writer_teardown_noop_total 20706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41795
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.862977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41795
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 387981
telemt_user_connections_current{user="hello"} 880
telemt_user_octets_from_client{user="hello"} 7579791053 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 198724763155 (185.08 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 130356.4 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9041766
telemt_connections_bad_total 1049321
telemt_connections_current 4813
telemt_connections_me_current 4813
telemt_handshake_timeouts_total 250023
telemt_upstream_connect_attempt_total 50627
telemt_upstream_connect_success_total 50434
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 50583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1897
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 2532516
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6691511
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 989
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
telemt_me_writers_active_current 45
telemt_desync_total 26853
telemt_desync_full_logged_total 8818
telemt_desync_suppressed_total 18035
telemt_desync_frames_bucket_total{bucket="1_2"} 6656
telemt_desync_frames_bucket_total{bucket="3_10"} 9783
telemt_desync_frames_bucket_total{bucket="gt_10"} 10414
telemt_pool_swap_total 144
telemt_pool_force_close_total 3871
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 45689
telemt_me_writer_removed_unexpected_total 961
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41818
telemt_me_writer_teardown_success_total{mode="normal"} 46680
telemt_me_writer_teardown_noop_total 45691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.610324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 901
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6664502
telemt_user_connections_current{user="hello"} 4813
telemt_user_octets_from_client{user="hello"} 130017130012 (121.09 GB)
telemt_user_octets_to_client{user="hello"} 3136611448560 (2.85 TB)
telemt_user_unique_ips_current{user="hello"} 1849
telemt_user_unique_ips_recent_window{user="hello"} 659
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 130353.2 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7849864
telemt_connections_bad_total 876667
telemt_connections_current 4340
telemt_connections_me_current 4340
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 208364
telemt_upstream_connect_attempt_total 66674
telemt_upstream_connect_success_total 66159
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 66607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 6391
telemt_me_reconnect_success_total 1459
telemt_me_reader_eof_total 1310
telemt_me_idle_close_by_peer_total 1310
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2672661
telemt_me_route_drop_channel_closed_total 230
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5971865
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 987
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
telemt_me_writers_active_current 44
telemt_desync_total 25763
telemt_desync_full_logged_total 8567
telemt_desync_suppressed_total 17196
telemt_desync_frames_bucket_total{bucket="1_2"} 6347
telemt_desync_frames_bucket_total{bucket="3_10"} 9465
telemt_desync_frames_bucket_total{bucket="gt_10"} 9951
telemt_pool_swap_total 141
telemt_pool_force_close_total 3818
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 44326
telemt_me_writer_removed_unexpected_total 1325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41468
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40508
telemt_me_writer_teardown_success_total{mode="normal"} 45713
telemt_me_writer_teardown_noop_total 44330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.895726
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1143
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5972661
telemt_user_connections_current{user="hello"} 4340
telemt_user_octets_from_client{user="hello"} 109791371501 (102.25 GB)
telemt_user_octets_to_client{user="hello"} 2577640092740 (2.34 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1719
telemt_user_unique_ips_recent_window{user="hello"} 624
```