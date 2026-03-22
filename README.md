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

# Server Metrics 2026-03-22 04:23:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 26205.1 (7h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417978
telemt_connections_bad_total 26830
telemt_connections_current 1107
telemt_connections_me_current 1107
telemt_handshake_timeouts_total 23607
telemt_upstream_connect_attempt_total 10985
telemt_upstream_connect_success_total 10984
telemt_upstream_connect_attempts_per_request{bucket="1"} 10984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 296
telemt_me_reconnect_success_total 169
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 85801
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345298
telemt_me_endpoint_quarantine_total 208
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 3126
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 2274
telemt_desync_frames_bucket_total{bucket="1_2"} 1078
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 29
telemt_pool_force_close_total 734
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 9901
telemt_me_writer_removed_unexpected_total 163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 729
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9167
telemt_me_writer_teardown_success_total{mode="normal"} 10056
telemt_me_writer_teardown_noop_total 9902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.590947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 152
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 344393
telemt_user_connections_current{user="hello"} 1107
telemt_user_octets_from_client{user="hello"} 4287521300 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 120215178032 (111.96 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 39571.5 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873877
telemt_connections_bad_total 58495
telemt_connections_current 878
telemt_connections_me_current 878
telemt_handshake_timeouts_total 31208
telemt_upstream_connect_attempt_total 18504
telemt_upstream_connect_success_total 18219
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 18477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 1508
telemt_me_reconnect_success_total 558
telemt_me_reader_eof_total 495
telemt_me_idle_close_by_peer_total 495
telemt_me_route_drop_no_conn_total 356406
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692946
telemt_me_endpoint_quarantine_total 367
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 319
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
telemt_desync_total 2960
telemt_desync_full_logged_total 1698
telemt_desync_suppressed_total 1262
telemt_desync_frames_bucket_total{bucket="1_2"} 627
telemt_desync_frames_bucket_total{bucket="3_10"} 1139
telemt_desync_frames_bucket_total{bucket="gt_10"} 1194
telemt_pool_swap_total 42
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16431
telemt_me_writer_removed_unexpected_total 471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15557
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15307
telemt_me_writer_teardown_success_total{mode="normal"} 16913
telemt_me_writer_teardown_noop_total 16431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33344
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.909279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33344
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 691888
telemt_user_connections_current{user="hello"} 878
telemt_user_octets_from_client{user="hello"} 11136568096 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 250465331548 (233.26 GB)
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 114431.3 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7995861
telemt_connections_bad_total 675489
telemt_connections_current 2693
telemt_connections_me_current 2693
telemt_handshake_timeouts_total 262646
telemt_upstream_connect_attempt_total 42742
telemt_upstream_connect_success_total 42664
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 42672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1632
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 4579959
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6447563
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 858
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
telemt_me_writers_active_current 44
telemt_desync_total 27042
telemt_desync_full_logged_total 8981
telemt_desync_suppressed_total 18061
telemt_desync_frames_bucket_total{bucket="1_2"} 5846
telemt_desync_frames_bucket_total{bucket="3_10"} 10570
telemt_desync_frames_bucket_total{bucket="gt_10"} 10626
telemt_pool_swap_total 124
telemt_pool_force_close_total 4046
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 615
telemt_me_draining_writers_reap_progress_total 38982
telemt_me_writer_removed_unexpected_total 826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36106
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34936
telemt_me_writer_teardown_success_total{mode="normal"} 39343
telemt_me_writer_teardown_noop_total 39026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.452393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 615
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 757
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6439363
telemt_user_connections_current{user="hello"} 2693
telemt_user_octets_from_client{user="hello"} 109536646156 (102.01 GB)
telemt_user_octets_to_client{user="hello"} 2164517530460 (1.97 TB)
telemt_user_unique_ips_current{user="hello"} 1254
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 114432.7 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6605655
telemt_connections_bad_total 594475
telemt_connections_current 2340
telemt_connections_me_current 2340
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 219127
telemt_upstream_connect_attempt_total 46682
telemt_upstream_connect_success_total 46285
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 46485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1975
telemt_me_reconnect_success_total 904
telemt_me_reader_eof_total 878
telemt_me_idle_close_by_peer_total 878
telemt_me_route_drop_no_conn_total 2292767
telemt_me_route_drop_channel_closed_total 281
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4930445
telemt_me_endpoint_quarantine_total 726
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 882
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
telemt_me_writers_active_current 43
telemt_desync_total 23052
telemt_desync_full_logged_total 7875
telemt_desync_suppressed_total 15177
telemt_desync_frames_bucket_total{bucket="1_2"} 5538
telemt_desync_frames_bucket_total{bucket="3_10"} 8953
telemt_desync_frames_bucket_total{bucket="gt_10"} 8561
telemt_pool_swap_total 125
telemt_pool_force_close_total 3678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 37433
telemt_me_writer_removed_unexpected_total 860
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3091
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35142
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3461
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 217
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33755
telemt_me_writer_teardown_success_total{mode="normal"} 38233
telemt_me_writer_teardown_noop_total 37439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75672
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.510062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75672
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4852131
telemt_user_connections_current{user="hello"} 2340
telemt_user_octets_from_client{user="hello"} 143360031425 (133.51 GB)
telemt_user_octets_to_client{user="hello"} 2311420614475 (2.10 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1079
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 114396.9 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6466698
telemt_connections_bad_total 552428
telemt_connections_current 1839
telemt_connections_me_current 1839
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 213621
telemt_upstream_connect_attempt_total 53131
telemt_upstream_connect_success_total 52637
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 52779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2303
telemt_me_reconnect_success_total 1024
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 2247671
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4805962
telemt_me_endpoint_quarantine_total 808
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 850
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 37
telemt_desync_total 22939
telemt_desync_full_logged_total 7761
telemt_desync_suppressed_total 15178
telemt_desync_frames_bucket_total{bucket="1_2"} 5600
telemt_desync_frames_bucket_total{bucket="3_10"} 8798
telemt_desync_frames_bucket_total{bucket="gt_10"} 8541
telemt_pool_swap_total 122
telemt_pool_force_close_total 3553
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 38584
telemt_me_writer_removed_unexpected_total 951
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36286
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 234
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35031
telemt_me_writer_teardown_success_total{mode="normal"} 39553
telemt_me_writer_teardown_noop_total 38596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78149
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.271612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78149
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 4800892
telemt_user_connections_current{user="hello"} 1839
telemt_user_octets_from_client{user="hello"} 135570411687 (126.26 GB)
telemt_user_octets_to_client{user="hello"} 2196996790303 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 114436.7 (31h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20776299
telemt_connections_bad_total 1725260
telemt_connections_current 3163
telemt_connections_me_current 3163
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 628772
telemt_upstream_connect_attempt_total 203501
telemt_upstream_connect_success_total 185203
telemt_upstream_connect_fail_total 16472
telemt_upstream_connect_attempts_per_request{bucket="1"} 201675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8950
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16472
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65171
telemt_me_reconnect_success_total 2422
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1507
telemt_me_route_drop_no_conn_total 39596036
telemt_me_route_drop_channel_closed_total 128
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16722971
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 144
telemt_me_single_endpoint_outage_exit_total 144
telemt_me_single_endpoint_outage_reconnect_attempt_total 297
telemt_me_single_endpoint_outage_reconnect_success_total 76
telemt_me_single_endpoint_quarantine_bypass_total 297
telemt_me_single_endpoint_shadow_rotate_total 900
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 32439
telemt_desync_full_logged_total 9759
telemt_desync_suppressed_total 22680
telemt_desync_frames_bucket_total{bucket="1_2"} 7049
telemt_desync_frames_bucket_total{bucket="3_10"} 14386
telemt_desync_frames_bucket_total{bucket="gt_10"} 11004
telemt_pool_swap_total 119
telemt_pool_force_close_total 3806
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 833
telemt_me_draining_writers_reap_progress_total 35885
telemt_me_writer_removed_unexpected_total 2247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3272
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 534
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32079
telemt_me_writer_teardown_success_total{mode="normal"} 37877
telemt_me_writer_teardown_noop_total 35912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73789
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.953721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73789
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 833
telemt_me_refill_failed_total 3809
telemt_me_writer_restored_same_endpoint_total 1645
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 16857707
telemt_user_connections_current{user="hello"} 3163
telemt_user_octets_from_client{user="hello"} 238872997160 (222.47 GB)
telemt_user_octets_to_client{user="hello"} 1276896513067 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1372
telemt_user_unique_ips_recent_window{user="hello"} 389
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 114403.6 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6241250
telemt_connections_bad_total 603513
telemt_connections_current 2228
telemt_connections_me_current 2228
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 131558
telemt_upstream_connect_attempt_total 61537
telemt_upstream_connect_success_total 60839
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 61434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_reconnect_attempts_total 69833
telemt_me_reconnect_success_total 1839
telemt_me_reader_eof_total 1622
telemt_me_idle_close_by_peer_total 1621
telemt_me_route_drop_no_conn_total 2424479
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4840830
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 868
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
telemt_desync_total 24186
telemt_desync_full_logged_total 8476
telemt_desync_suppressed_total 15710
telemt_desync_frames_bucket_total{bucket="1_2"} 4735
telemt_desync_frames_bucket_total{bucket="3_10"} 9355
telemt_desync_frames_bucket_total{bucket="gt_10"} 10096
telemt_pool_swap_total 119
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 405
telemt_me_draining_writers_reap_progress_total 40442
telemt_me_writer_removed_unexpected_total 1658
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4104
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37068
telemt_me_writer_teardown_success_total{mode="normal"} 42133
telemt_me_writer_teardown_noop_total 40443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.345415
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 405
telemt_me_refill_failed_total 4213
telemt_me_writer_restored_same_endpoint_total 1543
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4833253
telemt_user_connections_current{user="hello"} 2228
telemt_user_octets_from_client{user="hello"} 126904905616 (118.19 GB)
telemt_user_octets_to_client{user="hello"} 1990830809170 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1036
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51239.4 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4188345
telemt_connections_bad_total 177598
telemt_connections_current 1803
telemt_connections_me_current 1803
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1677330
telemt_upstream_connect_attempt_total 30356
telemt_upstream_connect_success_total 30159
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 30349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_reconnect_attempts_total 45972
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 696
telemt_me_idle_close_by_peer_total 696
telemt_me_route_drop_no_conn_total 1050874
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2052010
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11028
telemt_desync_full_logged_total 3811
telemt_desync_suppressed_total 7217
telemt_desync_frames_bucket_total{bucket="1_2"} 2054
telemt_desync_frames_bucket_total{bucket="3_10"} 4232
telemt_desync_frames_bucket_total{bucket="gt_10"} 4742
telemt_pool_swap_total 55
telemt_pool_force_close_total 1620
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 19141
telemt_me_writer_removed_unexpected_total 768
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1665
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18272
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1413
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17521
telemt_me_writer_teardown_success_total{mode="normal"} 19937
telemt_me_writer_teardown_noop_total 19143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.512175
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 902
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2055434
telemt_user_connections_current{user="hello"} 1803
telemt_user_octets_from_client{user="hello"} 56112383376 (52.26 GB)
telemt_user_octets_to_client{user="hello"} 884633230162 (823.88 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 882
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 32210.9 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227525
telemt_connections_bad_total 1835
telemt_connections_current 407
telemt_connections_me_current 407
telemt_handshake_timeouts_total 5997
telemt_upstream_connect_attempt_total 15601
telemt_upstream_connect_success_total 15565
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 348
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 63135
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201613
telemt_me_endpoint_quarantine_total 309
telemt_me_single_endpoint_shadow_rotate_total 279
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1140
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 35
telemt_pool_force_close_total 781
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 14110
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13432
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13329
telemt_me_writer_teardown_success_total{mode="normal"} 14318
telemt_me_writer_teardown_noop_total 14110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28428
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.112762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28428
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 201270
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3478576004 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 121549254280 (113.20 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 114408.0 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7559995
telemt_connections_bad_total 759070
telemt_connections_current 2338
telemt_connections_me_current 2338
telemt_handshake_timeouts_total 215522
telemt_upstream_connect_attempt_total 45134
telemt_upstream_connect_success_total 44970
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 45097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_route_drop_no_conn_total 2161389
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5634499
telemt_me_endpoint_quarantine_total 823
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 879
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
telemt_me_writers_active_current 43
telemt_desync_total 22069
telemt_desync_full_logged_total 7259
telemt_desync_suppressed_total 14810
telemt_desync_frames_bucket_total{bucket="1_2"} 5526
telemt_desync_frames_bucket_total{bucket="3_10"} 8013
telemt_desync_frames_bucket_total{bucket="gt_10"} 8530
telemt_pool_swap_total 127
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 398
telemt_me_draining_writers_reap_progress_total 40718
telemt_me_writer_removed_unexpected_total 837
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37357
telemt_me_writer_teardown_success_total{mode="normal"} 41579
telemt_me_writer_teardown_noop_total 40720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.731039
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 398
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 790
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5609341
telemt_user_connections_current{user="hello"} 2338
telemt_user_octets_from_client{user="hello"} 111451953276 (103.80 GB)
telemt_user_octets_to_client{user="hello"} 2614319993180 (2.38 TB)
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 114404.7 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6554679
telemt_connections_bad_total 643727
telemt_connections_current 2341
telemt_connections_me_current 2341
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 177137
telemt_upstream_connect_attempt_total 60925
telemt_upstream_connect_success_total 60462
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 60865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 5688
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 1113
telemt_me_idle_close_by_peer_total 1113
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2215209
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5001857
telemt_me_endpoint_quarantine_total 898
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 875
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
telemt_me_writers_warm_current 34
telemt_desync_total 20722
telemt_desync_full_logged_total 6914
telemt_desync_suppressed_total 13808
telemt_desync_frames_bucket_total{bucket="1_2"} 5277
telemt_desync_frames_bucket_total{bucket="3_10"} 7585
telemt_desync_frames_bucket_total{bucket="gt_10"} 7860
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 39235
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36703
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35924
telemt_me_writer_teardown_success_total{mode="normal"} 40415
telemt_me_writer_teardown_noop_total 39239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.302502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5004687
telemt_user_connections_current{user="hello"} 2341
telemt_user_octets_from_client{user="hello"} 94436023813 (87.95 GB)
telemt_user_octets_to_client{user="hello"} 2144143547544 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 288
```