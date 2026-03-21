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

# Server Metrics 2026-03-21 22:06:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 3581.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70905
telemt_connections_bad_total 5311
telemt_connections_current 732
telemt_connections_me_current 732
telemt_handshake_timeouts_total 3311
telemt_upstream_connect_attempt_total 1421
telemt_upstream_connect_success_total 1420
telemt_upstream_connect_attempts_per_request{bucket="1"} 1420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 31
telemt_me_reconnect_success_total 11
telemt_me_reader_eof_total 13
telemt_me_idle_close_by_peer_total 13
telemt_me_route_drop_no_conn_total 15801
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56873
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 30
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
telemt_desync_total 401
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 3
telemt_pool_force_close_total 76
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 1226
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1171
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1150
telemt_me_writer_teardown_success_total{mode="normal"} 1239
telemt_me_writer_teardown_noop_total 1226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.992029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 56828
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 778981496 (742.89 MB)
telemt_user_octets_to_client{user="hello"} 19060245000 (17.75 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 16947.4 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583535
telemt_connections_bad_total 27645
telemt_connections_current 921
telemt_connections_me_current 921
telemt_handshake_timeouts_total 20712
telemt_upstream_connect_attempt_total 6847
telemt_upstream_connect_success_total 6716
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 6832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 598
telemt_me_reconnect_success_total 216
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 307170
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 473117
telemt_me_endpoint_quarantine_total 137
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 135
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
telemt_me_writers_active_current 46
telemt_desync_total 2112
telemt_desync_full_logged_total 1201
telemt_desync_suppressed_total 911
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 18
telemt_pool_force_close_total 528
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 5996
telemt_me_writer_removed_unexpected_total 172
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5645
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5468
telemt_me_writer_teardown_success_total{mode="normal"} 6166
telemt_me_writer_teardown_noop_total 5996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.918019
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 147
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 472485
telemt_user_connections_current{user="hello"} 921
telemt_user_octets_from_client{user="hello"} 8245821048 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 158073248812 (147.22 GB)
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 91807.4 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7196012
telemt_connections_bad_total 554541
telemt_connections_current 2860
telemt_connections_me_current 2860
telemt_handshake_timeouts_total 224631
telemt_upstream_connect_attempt_total 32975
telemt_upstream_connect_success_total 32907
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 32914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1445
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 709
telemt_me_idle_close_by_peer_total 709
telemt_me_route_drop_no_conn_total 4447769
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5886439
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 678
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 24855
telemt_desync_full_logged_total 8175
telemt_desync_suppressed_total 16680
telemt_desync_frames_bucket_total{bucket="1_2"} 5346
telemt_desync_frames_bucket_total{bucket="3_10"} 9738
telemt_desync_frames_bucket_total{bucket="gt_10"} 9771
telemt_pool_swap_total 98
telemt_pool_force_close_total 3315
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 545
telemt_me_draining_writers_reap_progress_total 30035
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2566
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27743
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3077
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26720
telemt_me_writer_teardown_success_total{mode="normal"} 30309
telemt_me_writer_teardown_noop_total 30079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60388
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 147.758933
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60388
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 545
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5879302
telemt_user_connections_current{user="hello"} 2860
telemt_user_octets_from_client{user="hello"} 101085065808 (94.14 GB)
telemt_user_octets_to_client{user="hello"} 1897833530688 (1.73 TB)
telemt_user_unique_ips_current{user="hello"} 1258
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 91808.5 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5894886
telemt_connections_bad_total 572038
telemt_connections_current 2269
telemt_connections_me_current 2269
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 192285
telemt_upstream_connect_attempt_total 36930
telemt_upstream_connect_success_total 36598
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 36770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1724
telemt_me_reconnect_success_total 729
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 2057561
telemt_me_route_drop_channel_closed_total 236
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4398204
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 699
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
telemt_desync_total 21209
telemt_desync_full_logged_total 7073
telemt_desync_suppressed_total 14136
telemt_desync_frames_bucket_total{bucket="1_2"} 5128
telemt_desync_frames_bucket_total{bucket="3_10"} 8204
telemt_desync_frames_bucket_total{bucket="gt_10"} 7877
telemt_pool_swap_total 100
telemt_pool_force_close_total 3037
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28639
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2469
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26783
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25602
telemt_me_writer_teardown_success_total{mode="normal"} 29252
telemt_me_writer_teardown_noop_total 28645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57897
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.431198
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57897
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4371269
telemt_user_connections_current{user="hello"} 2269
telemt_user_octets_from_client{user="hello"} 135116001725 (125.84 GB)
telemt_user_octets_to_client{user="hello"} 2030913730047 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1007
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 91773.6 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5817058
telemt_connections_bad_total 530233
telemt_connections_current 1914
telemt_connections_me_current 1914
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 181273
telemt_upstream_connect_attempt_total 43373
telemt_upstream_connect_success_total 43081
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1760
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 2060210
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4359635
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 684
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
telemt_desync_total 21015
telemt_desync_full_logged_total 6902
telemt_desync_suppressed_total 14113
telemt_desync_frames_bucket_total{bucket="1_2"} 5211
telemt_desync_frames_bucket_total{bucket="3_10"} 7970
telemt_desync_frames_bucket_total{bucket="gt_10"} 7834
telemt_pool_swap_total 98
telemt_pool_force_close_total 2913
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 30085
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28244
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2698
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27172
telemt_me_writer_teardown_success_total{mode="normal"} 30798
telemt_me_writer_teardown_noop_total 30095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.771546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 4361377
telemt_user_connections_current{user="hello"} 1914
telemt_user_octets_from_client{user="hello"} 127865933003 (119.08 GB)
telemt_user_octets_to_client{user="hello"} 1993113212415 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 885
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 91811.9 (25h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19582806
telemt_connections_bad_total 1352172
telemt_connections_current 2901
telemt_connections_me_current 2901
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 555134
telemt_upstream_connect_attempt_total 183032
telemt_upstream_connect_success_total 165721
telemt_upstream_connect_fail_total 15820
telemt_upstream_connect_attempts_per_request{bucket="1"} 181541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8857
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15820
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59724
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 39385442
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16034239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 665
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 711
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
telemt_desync_total 30577
telemt_desync_full_logged_total 9050
telemt_desync_suppressed_total 21527
telemt_desync_frames_bucket_total{bucket="1_2"} 6685
telemt_desync_frames_bucket_total{bucket="3_10"} 13556
telemt_desync_frames_bucket_total{bucket="gt_10"} 10336
telemt_pool_swap_total 93
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 28324
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26037
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25174
telemt_me_writer_teardown_success_total{mode="normal"} 29887
telemt_me_writer_teardown_noop_total 28350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58237
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 207.261657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58237
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16159251
telemt_user_connections_current{user="hello"} 2901
telemt_user_octets_from_client{user="hello"} 167312826822 (155.82 GB)
telemt_user_octets_to_client{user="hello"} 1036415900882 (965.24 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1230
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 91779.2 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5650671
telemt_connections_bad_total 531750
telemt_connections_current 2248
telemt_connections_me_current 2248
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 116974
telemt_upstream_connect_attempt_total 50753
telemt_upstream_connect_success_total 50225
telemt_upstream_connect_fail_total 442
telemt_upstream_connect_attempts_per_request{bucket="1"} 50667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 442
telemt_me_reconnect_attempts_total 11325
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 2320932
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4396623
telemt_me_endpoint_quarantine_total 566
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 682
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
telemt_me_writers_active_current 46
telemt_desync_total 22104
telemt_desync_full_logged_total 7665
telemt_desync_suppressed_total 14439
telemt_desync_frames_bucket_total{bucket="1_2"} 4226
telemt_desync_frames_bucket_total{bucket="3_10"} 8579
telemt_desync_frames_bucket_total{bucket="gt_10"} 9299
telemt_pool_swap_total 93
telemt_pool_force_close_total 2729
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 354
telemt_me_draining_writers_reap_progress_total 31018
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29089
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28289
telemt_me_writer_teardown_success_total{mode="normal"} 32257
telemt_me_writer_teardown_noop_total 31019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.614818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 354
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1106
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4390005
telemt_user_connections_current{user="hello"} 2248
telemt_user_octets_from_client{user="hello"} 116867533676 (108.84 GB)
telemt_user_octets_to_client{user="hello"} 1783477878870 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 28615.1 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3449195
telemt_connections_bad_total 123941
telemt_connections_current 1879
telemt_connections_me_current 1879
telemt_handshake_timeouts_total 1456089
telemt_upstream_connect_attempt_total 9648
telemt_upstream_connect_success_total 9527
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 9642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 2345
telemt_me_reconnect_success_total 328
telemt_me_reader_eof_total 244
telemt_me_idle_close_by_peer_total 244
telemt_me_route_drop_no_conn_total 964684
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1653058
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 213
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
telemt_desync_total 9114
telemt_desync_full_logged_total 3068
telemt_desync_suppressed_total 6046
telemt_desync_frames_bucket_total{bucket="1_2"} 1634
telemt_desync_frames_bucket_total{bucket="3_10"} 3478
telemt_desync_frames_bucket_total{bucket="gt_10"} 4002
telemt_pool_swap_total 30
telemt_pool_force_close_total 971
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 91
telemt_me_draining_writers_reap_progress_total 8429
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7940
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7458
telemt_me_writer_teardown_success_total{mode="normal"} 8705
telemt_me_writer_teardown_noop_total 8430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.559236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 91
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1648268
telemt_user_connections_current{user="hello"} 1879
telemt_user_octets_from_client{user="hello"} 47758015744 (44.48 GB)
telemt_user_octets_to_client{user="hello"} 708185723640 (659.55 GB)
telemt_user_unique_ips_current{user="hello"} 866
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 9586.1 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120278
telemt_connections_bad_total 1295
telemt_connections_current 456
telemt_connections_me_current 456
telemt_handshake_timeouts_total 3226
telemt_upstream_connect_attempt_total 4101
telemt_upstream_connect_success_total 4089
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 75
telemt_me_reconnect_success_total 43
telemt_me_reader_eof_total 43
telemt_me_idle_close_by_peer_total 43
telemt_me_route_drop_no_conn_total 33744
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103459
telemt_me_endpoint_quarantine_total 71
telemt_me_single_endpoint_shadow_rotate_total 85
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
telemt_me_writers_active_current 44
telemt_desync_total 885
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 674
telemt_desync_frames_bucket_total{bucket="1_2"} 373
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 10
telemt_pool_force_close_total 262
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3627
telemt_me_writer_removed_unexpected_total 43
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 227
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3443
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3365
telemt_me_writer_teardown_success_total{mode="normal"} 3670
telemt_me_writer_teardown_noop_total 3627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.529563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 103312
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 2186302904 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 64726896584 (60.28 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 91783.8 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6731735
telemt_connections_bad_total 680012
telemt_connections_current 2517
telemt_connections_me_current 2517
telemt_handshake_timeouts_total 193948
telemt_upstream_connect_attempt_total 34679
telemt_upstream_connect_success_total 34541
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_reconnect_attempts_total 1419
telemt_me_reconnect_success_total 723
telemt_me_reader_eof_total 699
telemt_me_idle_close_by_peer_total 699
telemt_me_route_drop_no_conn_total 2056188
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5148723
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 698
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
telemt_desync_total 19718
telemt_desync_full_logged_total 6584
telemt_desync_suppressed_total 13134
telemt_desync_frames_bucket_total{bucket="1_2"} 4797
telemt_desync_frames_bucket_total{bucket="3_10"} 7191
telemt_desync_frames_bucket_total{bucket="gt_10"} 7730
telemt_pool_swap_total 101
telemt_pool_force_close_total 2764
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31170
telemt_me_writer_removed_unexpected_total 680
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2517
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29342
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28406
telemt_me_writer_teardown_success_total{mode="normal"} 31859
telemt_me_writer_teardown_noop_total 31172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63031
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.146772
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63031
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 647
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 5124243
telemt_user_connections_current{user="hello"} 2517
telemt_user_octets_from_client{user="hello"} 103561749980 (96.45 GB)
telemt_user_octets_to_client{user="hello"} 2404327309892 (2.19 TB)
telemt_user_unique_ips_current{user="hello"} 1025
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 91780.3 (25h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5741498
telemt_connections_bad_total 544986
telemt_connections_current 2238
telemt_connections_me_current 2238
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162314
telemt_upstream_connect_attempt_total 50881
telemt_upstream_connect_success_total 50499
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 50822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 5208
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2109322
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4512960
telemt_me_endpoint_quarantine_total 719
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 696
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
telemt_me_writers_active_current 51
telemt_desync_total 18348
telemt_desync_full_logged_total 6203
telemt_desync_suppressed_total 12145
telemt_desync_frames_bucket_total{bucket="1_2"} 4554
telemt_desync_frames_bucket_total{bucket="3_10"} 6705
telemt_desync_frames_bucket_total{bucket="gt_10"} 7089
telemt_pool_swap_total 99
telemt_pool_force_close_total 2713
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 30177
telemt_me_writer_removed_unexpected_total 919
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2500
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27464
telemt_me_writer_teardown_success_total{mode="normal"} 31138
telemt_me_writer_teardown_noop_total 30181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61319
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.217862
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61319
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 4516612
telemt_user_connections_current{user="hello"} 2238
telemt_user_octets_from_client{user="hello"} 86831160149 (80.87 GB)
telemt_user_octets_to_client{user="hello"} 1929893165620 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 259
```