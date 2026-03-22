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

# Server Metrics 2026-03-22 05:34:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 30502.2 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529332
telemt_connections_bad_total 35532
telemt_connections_current 1211
telemt_connections_me_current 1211
telemt_handshake_timeouts_total 27989
telemt_upstream_connect_attempt_total 12571
telemt_upstream_connect_success_total 12570
telemt_upstream_connect_attempts_per_request{bucket="1"} 12570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 329
telemt_me_reconnect_success_total 197
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 113452
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 437492
telemt_me_endpoint_quarantine_total 233
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3874
telemt_desync_full_logged_total 1064
telemt_desync_suppressed_total 2810
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1470
telemt_desync_frames_bucket_total{bucket="gt_10"} 1103
telemt_pool_swap_total 33
telemt_pool_force_close_total 874
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 11358
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10484
telemt_me_writer_teardown_success_total{mode="normal"} 11536
telemt_me_writer_teardown_noop_total 11359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22895
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.249278
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22895
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 179
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 436516
telemt_user_connections_current{user="hello"} 1211
telemt_user_octets_from_client{user="hello"} 5876594900 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 155263345140 (144.60 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43868.3 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 985648
telemt_connections_bad_total 77585
telemt_connections_current 1284
telemt_connections_me_current 1284
telemt_handshake_timeouts_total 33594
telemt_upstream_connect_attempt_total 23352
telemt_upstream_connect_success_total 23030
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 23321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 634
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 377418
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765407
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_active_current 45
telemt_desync_total 3297
telemt_desync_full_logged_total 1906
telemt_desync_suppressed_total 1391
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1269
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 47
telemt_pool_force_close_total 1233
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 18114
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17110
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16881
telemt_me_writer_teardown_success_total{mode="normal"} 18657
telemt_me_writer_teardown_noop_total 18114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.137086
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 767118
telemt_user_connections_current{user="hello"} 1284
telemt_user_octets_from_client{user="hello"} 12199858219 (11.36 GB)
telemt_user_octets_to_client{user="hello"} 282485716730 (263.09 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 118728.2 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8290638
telemt_connections_bad_total 717373
telemt_connections_current 3700
telemt_connections_me_current 3700
telemt_handshake_timeouts_total 269624
telemt_upstream_connect_attempt_total 44213
telemt_upstream_connect_success_total 44135
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1648
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 872
telemt_me_idle_close_by_peer_total 872
telemt_me_route_drop_no_conn_total 4640590
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6642552
telemt_me_endpoint_quarantine_total 754
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 893
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
telemt_me_writers_active_current 47
telemt_desync_total 28054
telemt_desync_full_logged_total 9348
telemt_desync_suppressed_total 18706
telemt_desync_frames_bucket_total{bucket="1_2"} 6063
telemt_desync_frames_bucket_total{bucket="3_10"} 10971
telemt_desync_frames_bucket_total{bucket="gt_10"} 11020
telemt_pool_swap_total 128
telemt_pool_force_close_total 4206
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 40359
telemt_me_writer_removed_unexpected_total 840
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3329
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36153
telemt_me_writer_teardown_success_total{mode="normal"} 40728
telemt_me_writer_teardown_noop_total 40403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81131
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.346179
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81131
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 771
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6633903
telemt_user_connections_current{user="hello"} 3700
telemt_user_octets_from_client{user="hello"} 112709714952 (104.97 GB)
telemt_user_octets_to_client{user="hello"} 2253589556540 (2.05 TB)
telemt_user_unique_ips_current{user="hello"} 1553
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 118729.8 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6817752
telemt_connections_bad_total 603003
telemt_connections_current 2775
telemt_connections_me_current 2775
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 227792
telemt_upstream_connect_attempt_total 48139
telemt_upstream_connect_success_total 47739
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 47942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23569
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 2342606
telemt_me_route_drop_channel_closed_total 286
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5100469
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 915
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23686
telemt_desync_full_logged_total 8121
telemt_desync_suppressed_total 15565
telemt_desync_frames_bucket_total{bucket="1_2"} 5684
telemt_desync_frames_bucket_total{bucket="3_10"} 9194
telemt_desync_frames_bucket_total{bucket="gt_10"} 8808
telemt_pool_swap_total 129
telemt_pool_force_close_total 3825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 38766
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3199
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34941
telemt_me_writer_teardown_success_total{mode="normal"} 39593
telemt_me_writer_teardown_noop_total 38772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.680223
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 5021954
telemt_user_connections_current{user="hello"} 2775
telemt_user_octets_from_client{user="hello"} 146709216437 (136.63 GB)
telemt_user_octets_to_client{user="hello"} 2402956282303 (2.19 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1180
telemt_user_unique_ips_recent_window{user="hello"} 378
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 118696.4 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6659082
telemt_connections_bad_total 561978
telemt_connections_current 2777
telemt_connections_me_current 2777
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 222582
telemt_upstream_connect_attempt_total 54576
telemt_upstream_connect_success_total 54028
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2443
telemt_me_reconnect_success_total 1069
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2345215
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4956559
telemt_me_endpoint_quarantine_total 845
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_me_writers_active_current 44
telemt_desync_total 23556
telemt_desync_full_logged_total 7998
telemt_desync_suppressed_total 15558
telemt_desync_frames_bucket_total{bucket="1_2"} 5725
telemt_desync_frames_bucket_total{bucket="3_10"} 9025
telemt_desync_frames_bucket_total{bucket="gt_10"} 8806
telemt_pool_swap_total 127
telemt_pool_force_close_total 3692
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 39816
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37410
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3454
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36124
telemt_me_writer_teardown_success_total{mode="normal"} 40833
telemt_me_writer_teardown_noop_total 39828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.897209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 935
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 4951058
telemt_user_connections_current{user="hello"} 2777
telemt_user_octets_from_client{user="hello"} 137601176471 (128.15 GB)
telemt_user_octets_to_client{user="hello"} 2266973003411 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1137
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 118732.7 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21283736
telemt_connections_bad_total 1805052
telemt_connections_current 4136
telemt_connections_me_current 4136
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 649185
telemt_upstream_connect_attempt_total 210404
telemt_upstream_connect_success_total 191736
telemt_upstream_connect_fail_total 16757
telemt_upstream_connect_attempts_per_request{bucket="1"} 208493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9875
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16757
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65472
telemt_me_reconnect_success_total 2538
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1581
telemt_me_route_drop_no_conn_total 40190134
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17097951
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 924
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 33090
telemt_desync_full_logged_total 9988
telemt_desync_suppressed_total 23102
telemt_desync_frames_bucket_total{bucket="1_2"} 7221
telemt_desync_frames_bucket_total{bucket="3_10"} 14686
telemt_desync_frames_bucket_total{bucket="gt_10"} 11183
telemt_pool_swap_total 122
telemt_pool_force_close_total 3916
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 866
telemt_me_draining_writers_reap_progress_total 37347
telemt_me_writer_removed_unexpected_total 2361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 558
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33431
telemt_me_writer_teardown_success_total{mode="normal"} 39456
telemt_me_writer_teardown_noop_total 37374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76830
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.333118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76830
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 866
telemt_me_refill_failed_total 3813
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 17237383
telemt_user_connections_current{user="hello"} 4136
telemt_user_octets_from_client{user="hello"} 252374483153 (235.04 GB)
telemt_user_octets_to_client{user="hello"} 1333556127751 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1597
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 118700.1 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6431511
telemt_connections_bad_total 612780
telemt_connections_current 2996
telemt_connections_me_current 2996
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 135975
telemt_upstream_connect_attempt_total 63145
telemt_upstream_connect_success_total 62413
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 63039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_reconnect_attempts_total 69919
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1661
telemt_me_idle_close_by_peer_total 1660
telemt_me_route_drop_no_conn_total 2478556
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5003625
telemt_me_endpoint_quarantine_total 805
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 903
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 24930
telemt_desync_full_logged_total 8736
telemt_desync_suppressed_total 16194
telemt_desync_frames_bucket_total{bucket="1_2"} 4929
telemt_desync_frames_bucket_total{bucket="3_10"} 9625
telemt_desync_frames_bucket_total{bucket="gt_10"} 10376
telemt_pool_swap_total 123
telemt_pool_force_close_total 3520
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 41900
telemt_me_writer_removed_unexpected_total 1697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4229
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3114
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38380
telemt_me_writer_teardown_success_total{mode="normal"} 43629
telemt_me_writer_teardown_noop_total 41901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.265726
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 4214
telemt_me_writer_restored_same_endpoint_total 1576
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 4995677
telemt_user_connections_current{user="hello"} 2996
telemt_user_octets_from_client{user="hello"} 129613318048 (120.71 GB)
telemt_user_octets_to_client{user="hello"} 2078348048870 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1295
telemt_user_unique_ips_recent_window{user="hello"} 402
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55536.0 (15h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4451052
telemt_connections_bad_total 183909
telemt_connections_current 2432
telemt_connections_me_current 2432
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1761562
telemt_upstream_connect_attempt_total 31993
telemt_upstream_connect_success_total 31780
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 31986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_reconnect_attempts_total 46101
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1117421
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2202688
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 430
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11885
telemt_desync_full_logged_total 4081
telemt_desync_suppressed_total 7804
telemt_desync_frames_bucket_total{bucket="1_2"} 2288
telemt_desync_frames_bucket_total{bucket="3_10"} 4551
telemt_desync_frames_bucket_total{bucket="gt_10"} 5046
telemt_pool_swap_total 60
telemt_pool_force_close_total 1761
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 20607
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19675
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18846
telemt_me_writer_teardown_success_total{mode="normal"} 21434
telemt_me_writer_teardown_noop_total 20609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42043
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.699635
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42043
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2205044
telemt_user_connections_current{user="hello"} 2432
telemt_user_octets_from_client{user="hello"} 58936556812 (54.89 GB)
telemt_user_octets_to_client{user="hello"} 968194024646 (901.70 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1074
telemt_user_unique_ips_recent_window{user="hello"} 336
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36507.0 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260131
telemt_connections_bad_total 1943
telemt_connections_current 522
telemt_connections_me_current 522
telemt_handshake_timeouts_total 6702
telemt_upstream_connect_attempt_total 17640
telemt_upstream_connect_success_total 17596
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 17636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 420
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 73242
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232155
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 318
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1223
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 888
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 40
telemt_pool_force_close_total 891
telemt_me_writer_close_signal_drop_total 34
telemt_me_draining_writers_reap_progress_total 15978
telemt_me_writer_removed_unexpected_total 230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15204
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15087
telemt_me_writer_teardown_success_total{mode="normal"} 16219
telemt_me_writer_teardown_noop_total 15978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32197
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.259776
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32197
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 34
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 209
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 231782
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 3901963316 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 143076257684 (133.25 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 118704.7 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7790738
telemt_connections_bad_total 773637
telemt_connections_current 3129
telemt_connections_me_current 3129
telemt_handshake_timeouts_total 222089
telemt_upstream_connect_attempt_total 46747
telemt_upstream_connect_success_total 46577
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 46710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 1693
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 903
telemt_me_route_drop_no_conn_total 2211669
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5813060
telemt_me_endpoint_quarantine_total 847
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 911
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
telemt_desync_total 22703
telemt_desync_full_logged_total 7484
telemt_desync_suppressed_total 15219
telemt_desync_frames_bucket_total{bucket="1_2"} 5683
telemt_desync_frames_bucket_total{bucket="3_10"} 8238
telemt_desync_frames_bucket_total{bucket="gt_10"} 8782
telemt_pool_swap_total 131
telemt_pool_force_close_total 3491
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 411
telemt_me_draining_writers_reap_progress_total 42204
telemt_me_writer_removed_unexpected_total 866
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39805
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3403
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38713
telemt_me_writer_teardown_success_total{mode="normal"} 43097
telemt_me_writer_teardown_noop_total 42206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85303
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.005527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85303
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 411
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 5787608
telemt_user_connections_current{user="hello"} 3129
telemt_user_octets_from_client{user="hello"} 114288039268 (106.44 GB)
telemt_user_octets_to_client{user="hello"} 2708141082384 (2.46 TB)
telemt_user_unique_ips_current{user="hello"} 1246
telemt_user_unique_ips_recent_window{user="hello"} 418
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 118701.1 (32h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6778364
telemt_connections_bad_total 662752
telemt_connections_current 3083
telemt_connections_me_current 3083
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 183348
telemt_upstream_connect_attempt_total 62598
telemt_upstream_connect_success_total 62129
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 62538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_reconnect_attempts_total 5792
telemt_me_reconnect_success_total 1277
telemt_me_reader_eof_total 1147
telemt_me_idle_close_by_peer_total 1147
telemt_me_seq_mismatch_total 55
telemt_me_route_drop_no_conn_total 2268148
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5181417
telemt_me_endpoint_quarantine_total 936
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 908
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 21565
telemt_desync_full_logged_total 7185
telemt_desync_suppressed_total 14380
telemt_desync_frames_bucket_total{bucket="1_2"} 5425
telemt_desync_frames_bucket_total{bucket="3_10"} 7891
telemt_desync_frames_bucket_total{bucket="gt_10"} 8249
telemt_pool_swap_total 129
telemt_pool_force_close_total 3433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 40773
telemt_me_writer_removed_unexpected_total 1160
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37340
telemt_me_writer_teardown_success_total{mode="normal"} 41990
telemt_me_writer_teardown_noop_total 40777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.699509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 999
telemt_me_writer_restored_fallback_total 73
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5184006
telemt_user_connections_current{user="hello"} 3083
telemt_user_octets_from_client{user="hello"} 97157023745 (90.48 GB)
telemt_user_octets_to_client{user="hello"} 2245892283580 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1257
telemt_user_unique_ips_recent_window{user="hello"} 379
```