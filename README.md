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

# Server Metrics 2026-03-22 08:23:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40622.5 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949411
telemt_connections_bad_total 55984
telemt_connections_current 1679
telemt_connections_me_current 1679
telemt_handshake_timeouts_total 44116
telemt_upstream_connect_attempt_total 16250
telemt_upstream_connect_success_total 16249
telemt_upstream_connect_attempts_per_request{bucket="1"} 16249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 477
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 541995
telemt_me_route_drop_channel_closed_total 167
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789834
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_shadow_rotate_total 327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5883
telemt_desync_full_logged_total 1657
telemt_desync_suppressed_total 4226
telemt_desync_frames_bucket_total{bucket="1_2"} 1816
telemt_desync_frames_bucket_total{bucket="3_10"} 2212
telemt_desync_frames_bucket_total{bucket="gt_10"} 1855
telemt_pool_swap_total 45
telemt_pool_force_close_total 1240
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 14738
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13498
telemt_me_writer_teardown_success_total{mode="normal"} 14935
telemt_me_writer_teardown_noop_total 14740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.950212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 788339
telemt_user_connections_current{user="hello"} 1679
telemt_user_octets_from_client{user="hello"} 10698153396 (9.96 GB)
telemt_user_octets_to_client{user="hello"} 254387241320 (236.92 GB)
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 53988.6 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1435135
telemt_connections_bad_total 142869
telemt_connections_current 2485
telemt_connections_me_current 2485
telemt_handshake_timeouts_total 41948
telemt_upstream_connect_attempt_total 28321
telemt_upstream_connect_success_total 27902
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 28269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2355
telemt_me_reconnect_success_total 1054
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 603210
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1081318
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_writers_active_current 127
telemt_desync_total 4795
telemt_desync_full_logged_total 2776
telemt_desync_suppressed_total 2019
telemt_desync_frames_bucket_total{bucket="1_2"} 1041
telemt_desync_frames_bucket_total{bucket="3_10"} 1861
telemt_desync_frames_bucket_total{bucket="gt_10"} 1893
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 22024
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2165
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20773
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20544
telemt_me_writer_teardown_success_total{mode="normal"} 22938
telemt_me_writer_teardown_noop_total 22024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.947658
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 856
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 1082950
telemt_user_connections_current{user="hello"} 2485
telemt_user_octets_from_client{user="hello"} 16885177002 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 384347636899 (357.95 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1428
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 128850.0 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9575069
telemt_connections_bad_total 859279
telemt_connections_current 4514
telemt_connections_me_current 4514
telemt_handshake_timeouts_total 289736
telemt_upstream_connect_attempt_total 47630
telemt_upstream_connect_success_total 47550
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 984
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 5299206
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7512325
telemt_me_endpoint_quarantine_total 810
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 966
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
telemt_me_writers_active_current 44
telemt_desync_total 32653
telemt_desync_full_logged_total 10756
telemt_desync_suppressed_total 21897
telemt_desync_frames_bucket_total{bucket="1_2"} 7155
telemt_desync_frames_bucket_total{bucket="3_10"} 12657
telemt_desync_frames_bucket_total{bucket="gt_10"} 12841
telemt_pool_swap_total 139
telemt_pool_force_close_total 4596
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 697
telemt_me_draining_writers_reap_progress_total 43433
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 309
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38837
telemt_me_writer_teardown_success_total{mode="normal"} 43868
telemt_me_writer_teardown_noop_total 43477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 184.639402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 697
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 7502663
telemt_user_connections_current{user="hello"} 4514
telemt_user_octets_from_client{user="hello"} 124663451400 (116.10 GB)
telemt_user_octets_to_client{user="hello"} 2523382865768 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 1711
telemt_user_unique_ips_recent_window{user="hello"} 670
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 128849.9 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7833737
telemt_connections_bad_total 695867
telemt_connections_current 3776
telemt_connections_me_current 3776
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 253230
telemt_upstream_connect_attempt_total 53627
telemt_upstream_connect_success_total 53152
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 53395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2822
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 993
telemt_me_idle_close_by_peer_total 993
telemt_me_route_drop_no_conn_total 2630822
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5799297
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 995
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
telemt_me_writers_active_current 46
telemt_desync_total 26527
telemt_desync_full_logged_total 9086
telemt_desync_suppressed_total 17441
telemt_desync_frames_bucket_total{bucket="1_2"} 6358
telemt_desync_frames_bucket_total{bucket="3_10"} 10268
telemt_desync_frames_bucket_total{bucket="gt_10"} 9901
telemt_pool_swap_total 141
telemt_pool_force_close_total 4183
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 447
telemt_me_draining_writers_reap_progress_total 41640
telemt_me_writer_removed_unexpected_total 1014
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37457
telemt_me_writer_teardown_success_total{mode="normal"} 42567
telemt_me_writer_teardown_noop_total 41646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84213
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.115724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84213
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 447
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5721981
telemt_user_connections_current{user="hello"} 3776
telemt_user_octets_from_client{user="hello"} 158815547987 (147.91 GB)
telemt_user_octets_to_client{user="hello"} 2750882418582 (2.50 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1530
telemt_user_unique_ips_recent_window{user="hello"} 669
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 128813.8 (35h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7551295
telemt_connections_bad_total 624317
telemt_connections_current 3894
telemt_connections_me_current 3894
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 249775
telemt_upstream_connect_attempt_total 58031
telemt_upstream_connect_success_total 57357
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2818
telemt_me_reconnect_success_total 1215
telemt_me_reader_eof_total 1115
telemt_me_idle_close_by_peer_total 1115
telemt_me_route_drop_no_conn_total 3037922
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5630210
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 949
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
telemt_me_writers_active_current 43
telemt_desync_total 26363
telemt_desync_full_logged_total 8977
telemt_desync_suppressed_total 17386
telemt_desync_frames_bucket_total{bucket="1_2"} 6352
telemt_desync_frames_bucket_total{bucket="3_10"} 10123
telemt_desync_frames_bucket_total{bucket="gt_10"} 9888
telemt_pool_swap_total 138
telemt_pool_force_close_total 4081
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 473
telemt_me_draining_writers_reap_progress_total 42656
telemt_me_writer_removed_unexpected_total 1125
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3794
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39971
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38575
telemt_me_writer_teardown_success_total{mode="normal"} 43765
telemt_me_writer_teardown_noop_total 42668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.453392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 473
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 5623351
telemt_user_connections_current{user="hello"} 3894
telemt_user_octets_from_client{user="hello"} 146701277475 (136.63 GB)
telemt_user_octets_to_client{user="hello"} 2501859314115 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1631
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 128853.1 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24307939
telemt_connections_bad_total 1985319
telemt_connections_current 5713
telemt_connections_me_current 5713
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 700021
telemt_upstream_connect_attempt_total 241675
telemt_upstream_connect_success_total 221911
telemt_upstream_connect_fail_total 17762
telemt_upstream_connect_attempts_per_request{bucket="1"} 239673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17762
telemt_me_keepalive_timeout_total 481
telemt_me_reconnect_attempts_total 68111
telemt_me_reconnect_success_total 2743
telemt_me_reader_eof_total 1693
telemt_me_idle_close_by_peer_total 1691
telemt_me_route_drop_no_conn_total 47298125
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19667139
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 165
telemt_me_single_endpoint_outage_exit_total 165
telemt_me_single_endpoint_outage_reconnect_attempt_total 336
telemt_me_single_endpoint_outage_reconnect_success_total 87
telemt_me_single_endpoint_quarantine_bypass_total 336
telemt_me_single_endpoint_shadow_rotate_total 1012
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
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
telemt_me_writers_active_current 72
telemt_desync_total 38221
telemt_desync_full_logged_total 11270
telemt_desync_suppressed_total 26951
telemt_desync_frames_bucket_total{bucket="1_2"} 8485
telemt_desync_frames_bucket_total{bucket="3_10"} 16861
telemt_desync_frames_bucket_total{bucket="gt_10"} 12875
telemt_pool_swap_total 134
telemt_pool_force_close_total 4225
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 974
telemt_me_draining_writers_reap_progress_total 40078
telemt_me_writer_removed_unexpected_total 2515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 603
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35853
telemt_me_writer_teardown_success_total{mode="normal"} 42318
telemt_me_writer_teardown_noop_total 40110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82428
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.471318
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82428
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 974
telemt_me_refill_failed_total 3959
telemt_me_writer_restored_same_endpoint_total 1868
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 677
telemt_me_async_recovery_trigger_total 14906
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 19832539
telemt_user_connections_current{user="hello"} 5713
telemt_user_octets_from_client{user="hello"} 278740460783 (259.60 GB)
telemt_user_octets_to_client{user="hello"} 1443302591287 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2043
telemt_user_unique_ips_recent_window{user="hello"} 1546
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 128820.9 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7184721
telemt_connections_bad_total 650157
telemt_connections_current 4331
telemt_connections_me_current 4331
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 147473
telemt_upstream_connect_attempt_total 66467
telemt_upstream_connect_success_total 65681
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 66350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_reconnect_attempts_total 70260
telemt_me_reconnect_success_total 1987
telemt_me_reader_eof_total 1748
telemt_me_idle_close_by_peer_total 1747
telemt_me_route_drop_no_conn_total 2802568
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5643269
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 975
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
telemt_desync_total 28417
telemt_desync_full_logged_total 9889
telemt_desync_suppressed_total 18528
telemt_desync_frames_bucket_total{bucket="1_2"} 5688
telemt_desync_frames_bucket_total{bucket="3_10"} 10945
telemt_desync_frames_bucket_total{bucket="gt_10"} 11784
telemt_pool_swap_total 135
telemt_pool_force_close_total 3868
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 44805
telemt_me_writer_removed_unexpected_total 1778
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4504
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42105
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40937
telemt_me_writer_teardown_success_total{mode="normal"} 46609
telemt_me_writer_teardown_noop_total 44806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91415
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.242065
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91415
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 5633932
telemt_user_connections_current{user="hello"} 4331
telemt_user_octets_from_client{user="hello"} 142159417488 (132.40 GB)
telemt_user_octets_to_client{user="hello"} 2341221710254 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1744
telemt_user_unique_ips_recent_window{user="hello"} 644
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 65656.6 (18h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5587723
telemt_connections_bad_total 220578
telemt_connections_current 3943
telemt_connections_me_current 3943
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2218765
telemt_upstream_connect_attempt_total 35533
telemt_upstream_connect_success_total 35283
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 46414
telemt_me_reconnect_success_total 1155
telemt_me_reader_eof_total 838
telemt_me_idle_close_by_peer_total 838
telemt_me_route_drop_no_conn_total 1395352
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2797881
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 501
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15083
telemt_desync_full_logged_total 5151
telemt_desync_suppressed_total 9932
telemt_desync_frames_bucket_total{bucket="1_2"} 2937
telemt_desync_frames_bucket_total{bucket="3_10"} 5811
telemt_desync_frames_bucket_total{bucket="gt_10"} 6335
telemt_pool_swap_total 70
telemt_pool_force_close_total 2085
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 23723
telemt_me_writer_removed_unexpected_total 908
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21638
telemt_me_writer_teardown_success_total{mode="normal"} 24653
telemt_me_writer_teardown_noop_total 23729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.435869
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 2629
telemt_me_writer_restored_same_endpoint_total 1032
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4274
telemt_user_connections_total{user="hello"} 2799186
telemt_user_connections_current{user="hello"} 3943
telemt_user_octets_from_client{user="hello"} 71382879204 (66.48 GB)
telemt_user_octets_to_client{user="hello"} 1230758962514 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46627.7 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399966
telemt_connections_bad_total 2769
telemt_connections_current 1036
telemt_connections_me_current 1036
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8150
telemt_upstream_connect_attempt_total 24802
telemt_upstream_connect_success_total 24746
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 24798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 965
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 334
telemt_me_route_drop_no_conn_total 124024
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361210
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_active_current 48
telemt_desync_total 1647
telemt_desync_full_logged_total 481
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 51
telemt_pool_force_close_total 1142
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 19878
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18854
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18736
telemt_me_writer_teardown_success_total{mode="normal"} 20212
telemt_me_writer_teardown_noop_total 19878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.818795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 363404
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 6989431873 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 189978717291 (176.93 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 128825.7 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8832692
telemt_connections_bad_total 1003367
telemt_connections_current 5074
telemt_connections_me_current 5074
telemt_handshake_timeouts_total 245446
telemt_upstream_connect_attempt_total 50210
telemt_upstream_connect_success_total 50019
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 50166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1892
telemt_me_reconnect_success_total 1025
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 996
telemt_me_route_drop_no_conn_total 2468658
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6548266
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 977
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
telemt_me_writers_active_current 43
telemt_desync_total 26224
telemt_desync_full_logged_total 8616
telemt_desync_suppressed_total 17608
telemt_desync_frames_bucket_total{bucket="1_2"} 6471
telemt_desync_frames_bucket_total{bucket="3_10"} 9543
telemt_desync_frames_bucket_total{bucket="gt_10"} 10210
telemt_pool_swap_total 143
telemt_pool_force_close_total 3810
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 460
telemt_me_draining_writers_reap_progress_total 45283
telemt_me_writer_removed_unexpected_total 957
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3604
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41473
telemt_me_writer_teardown_success_total{mode="normal"} 46269
telemt_me_writer_teardown_noop_total 45285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91554
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.706171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91554
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 460
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6521437
telemt_user_connections_current{user="hello"} 5074
telemt_user_octets_from_client{user="hello"} 127610555536 (118.85 GB)
telemt_user_octets_to_client{user="hello"} 3063958438284 (2.79 TB)
telemt_user_unique_ips_current{user="hello"} 1948
telemt_user_unique_ips_recent_window{user="hello"} 887
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 128822.6 (35h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7688506
telemt_connections_bad_total 846501
telemt_connections_current 3910
telemt_connections_me_current 3910
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 205976
telemt_upstream_connect_attempt_total 66229
telemt_upstream_connect_success_total 65716
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 66162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_reconnect_attempts_total 6361
telemt_me_reconnect_success_total 1437
telemt_me_reader_eof_total 1290
telemt_me_idle_close_by_peer_total 1290
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2591742
telemt_me_route_drop_channel_closed_total 220
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5850497
telemt_me_endpoint_quarantine_total 1010
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 975
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
telemt_me_writers_active_current 40
telemt_desync_total 25148
telemt_desync_full_logged_total 8362
telemt_desync_suppressed_total 16786
telemt_desync_frames_bucket_total{bucket="1_2"} 6205
telemt_desync_frames_bucket_total{bucket="3_10"} 9249
telemt_desync_frames_bucket_total{bucket="gt_10"} 9694
telemt_pool_swap_total 140
telemt_pool_force_close_total 3759
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 43922
telemt_me_writer_removed_unexpected_total 1305
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41096
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3491
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 268
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40163
telemt_me_writer_teardown_success_total{mode="normal"} 45289
telemt_me_writer_teardown_noop_total 43926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.779460
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1123
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5851594
telemt_user_connections_current{user="hello"} 3910
telemt_user_octets_from_client{user="hello"} 107553085577 (100.17 GB)
telemt_user_octets_to_client{user="hello"} 2534511313012 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1559
telemt_user_unique_ips_recent_window{user="hello"} 802
```