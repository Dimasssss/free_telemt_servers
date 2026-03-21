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

# Server Metrics 2026-03-21 22:16:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 4191.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80346
telemt_connections_bad_total 6223
telemt_connections_current 711
telemt_connections_me_current 711
telemt_handshake_timeouts_total 3718
telemt_upstream_connect_attempt_total 1675
telemt_upstream_connect_success_total 1674
telemt_upstream_connect_attempts_per_request{bucket="1"} 1674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 17087
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64523
telemt_me_endpoint_quarantine_total 25
telemt_me_single_endpoint_shadow_rotate_total 38
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 47
telemt_desync_total 488
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 4
telemt_pool_force_close_total 102
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1441
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 94
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1371
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1339
telemt_me_writer_teardown_success_total{mode="normal"} 1465
telemt_me_writer_teardown_noop_total 1441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2906
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.105267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2906
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 64465
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 898157464 (856.55 MB)
telemt_user_octets_to_client{user="hello"} 22471213720 (20.93 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 17557.1 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592787
telemt_connections_bad_total 27861
telemt_connections_current 568
telemt_connections_me_current 568
telemt_handshake_timeouts_total 21310
telemt_upstream_connect_attempt_total 7150
telemt_upstream_connect_success_total 7013
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 7135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 621
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 191
telemt_me_idle_close_by_peer_total 191
telemt_me_route_drop_no_conn_total 309647
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481334
telemt_me_endpoint_quarantine_total 145
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 2136
telemt_desync_full_logged_total 1213
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 875
telemt_pool_swap_total 19
telemt_pool_force_close_total 554
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 6265
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5889
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5711
telemt_me_writer_teardown_success_total{mode="normal"} 6443
telemt_me_writer_teardown_noop_total 6265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.091190
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 480692
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 8334999828 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 161918589004 (150.80 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 92417.0 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7220347
telemt_connections_bad_total 554565
telemt_connections_current 2290
telemt_connections_me_current 2290
telemt_handshake_timeouts_total 226258
telemt_upstream_connect_attempt_total 33223
telemt_upstream_connect_success_total 33155
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1450
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 4455587
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5908365
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 683
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
telemt_me_writers_active_current 44
telemt_desync_total 24956
telemt_desync_full_logged_total 8207
telemt_desync_suppressed_total 16749
telemt_desync_frames_bucket_total{bucket="1_2"} 5369
telemt_desync_frames_bucket_total{bucket="3_10"} 9780
telemt_desync_frames_bucket_total{bucket="gt_10"} 9807
telemt_pool_swap_total 99
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 30258
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2592
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27944
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3106
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26913
telemt_me_writer_teardown_success_total{mode="normal"} 30536
telemt_me_writer_teardown_noop_total 30302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 149.158352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5901164
telemt_user_connections_current{user="hello"} 2290
telemt_user_octets_from_client{user="hello"} 101381918440 (94.42 GB)
telemt_user_octets_to_client{user="hello"} 1909172631848 (1.74 TB)
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 92418.6 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5918538
telemt_connections_bad_total 572921
telemt_connections_current 1993
telemt_connections_me_current 1993
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 193500
telemt_upstream_connect_attempt_total 37198
telemt_upstream_connect_success_total 36865
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 37038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17705
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1727
telemt_me_reconnect_success_total 732
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 2075960
telemt_me_route_drop_channel_closed_total 236
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4422192
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_active_current 44
telemt_desync_total 21332
telemt_desync_full_logged_total 7134
telemt_desync_suppressed_total 14198
telemt_desync_frames_bucket_total{bucket="1_2"} 5161
telemt_desync_frames_bucket_total{bucket="3_10"} 8245
telemt_desync_frames_bucket_total{bucket="gt_10"} 7926
telemt_pool_swap_total 101
telemt_pool_force_close_total 3065
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28891
telemt_me_writer_removed_unexpected_total 684
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27021
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25826
telemt_me_writer_teardown_success_total{mode="normal"} 29506
telemt_me_writer_teardown_noop_total 28897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.442060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4390262
telemt_user_connections_current{user="hello"} 1993
telemt_user_octets_from_client{user="hello"} 136061682969 (126.72 GB)
telemt_user_octets_to_client{user="hello"} 2042472010243 (1.86 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 92382.3 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5843284
telemt_connections_bad_total 531661
telemt_connections_current 1677
telemt_connections_me_current 1677
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 182532
telemt_upstream_connect_attempt_total 43600
telemt_upstream_connect_success_total 43305
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19144
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1776
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 740
telemt_me_idle_close_by_peer_total 740
telemt_me_route_drop_no_conn_total 2066033
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4376524
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 689
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
telemt_me_writers_active_current 42
telemt_desync_total 21135
telemt_desync_full_logged_total 6939
telemt_desync_suppressed_total 14196
telemt_desync_frames_bucket_total{bucket="1_2"} 5229
telemt_desync_frames_bucket_total{bucket="3_10"} 8016
telemt_desync_frames_bucket_total{bucket="gt_10"} 7890
telemt_pool_swap_total 99
telemt_pool_force_close_total 2941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30305
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27364
telemt_me_writer_teardown_success_total{mode="normal"} 31019
telemt_me_writer_teardown_noop_total 30316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.842777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4378218
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 129177552227 (120.31 GB)
telemt_user_octets_to_client{user="hello"} 2001402024351 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 862
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 92421.9 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19620747
telemt_connections_bad_total 1363130
telemt_connections_current 2726
telemt_connections_me_current 2726
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 557340
telemt_upstream_connect_attempt_total 183266
telemt_upstream_connect_success_total 165950
telemt_upstream_connect_fail_total 15820
telemt_upstream_connect_attempts_per_request{bucket="1"} 181770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8857
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15820
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59724
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 39394488
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16058077
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 672
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 717
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
telemt_desync_total 30673
telemt_desync_full_logged_total 9079
telemt_desync_suppressed_total 21594
telemt_desync_frames_bucket_total{bucket="1_2"} 6704
telemt_desync_frames_bucket_total{bucket="3_10"} 13598
telemt_desync_frames_bucket_total{bucket="gt_10"} 10371
telemt_pool_swap_total 94
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 721
telemt_me_draining_writers_reap_progress_total 28549
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2671
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25370
telemt_me_writer_teardown_success_total{mode="normal"} 30112
telemt_me_writer_teardown_noop_total 28575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.444786
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 721
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16183068
telemt_user_connections_current{user="hello"} 2726
telemt_user_octets_from_client{user="hello"} 169049278846 (157.44 GB)
telemt_user_octets_to_client{user="hello"} 1045282659262 (973.50 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1186
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 92389.3 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5670101
telemt_connections_bad_total 532534
telemt_connections_current 2198
telemt_connections_me_current 2198
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117604
telemt_upstream_connect_attempt_total 51010
telemt_upstream_connect_success_total 50481
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 50924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 11325
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 2325621
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4413336
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 690
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
telemt_me_writers_active_current 46
telemt_desync_total 22196
telemt_desync_full_logged_total 7715
telemt_desync_suppressed_total 14481
telemt_desync_frames_bucket_total{bucket="1_2"} 4234
telemt_desync_frames_bucket_total{bucket="3_10"} 8617
telemt_desync_frames_bucket_total{bucket="gt_10"} 9345
telemt_pool_swap_total 94
telemt_pool_force_close_total 2760
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 31264
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29320
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28504
telemt_me_writer_teardown_success_total{mode="normal"} 32503
telemt_me_writer_teardown_noop_total 31265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63768
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.619477
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63768
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1106
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4406677
telemt_user_connections_current{user="hello"} 2198
telemt_user_octets_from_client{user="hello"} 117190365144 (109.14 GB)
telemt_user_octets_to_client{user="hello"} 1790989531150 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 29225.1 (8h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3483274
telemt_connections_bad_total 124301
telemt_connections_current 1740
telemt_connections_me_current 1740
telemt_handshake_timeouts_total 1474308
telemt_upstream_connect_attempt_total 9954
telemt_upstream_connect_success_total 9830
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 9948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_reconnect_attempts_total 2367
telemt_me_reconnect_success_total 335
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 969165
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1668495
telemt_me_endpoint_quarantine_total 151
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 218
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
telemt_me_writers_active_current 45
telemt_desync_total 9167
telemt_desync_full_logged_total 3090
telemt_desync_suppressed_total 6077
telemt_desync_frames_bucket_total{bucket="1_2"} 1638
telemt_desync_frames_bucket_total{bucket="3_10"} 3501
telemt_desync_frames_bucket_total{bucket="gt_10"} 4028
telemt_pool_swap_total 31
telemt_pool_force_close_total 997
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 95
telemt_me_draining_writers_reap_progress_total 8696
telemt_me_writer_removed_unexpected_total 272
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8199
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7699
telemt_me_writer_teardown_success_total{mode="normal"} 8980
telemt_me_writer_teardown_noop_total 8697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.601689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 95
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1663677
telemt_user_connections_current{user="hello"} 1740
telemt_user_octets_from_client{user="hello"} 48155647956 (44.85 GB)
telemt_user_octets_to_client{user="hello"} 715494204904 (666.36 GB)
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 10196.2 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125089
telemt_connections_bad_total 1316
telemt_connections_current 449
telemt_connections_me_current 449
telemt_handshake_timeouts_total 3275
telemt_upstream_connect_attempt_total 4403
telemt_upstream_connect_success_total 4390
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 35545
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108084
telemt_me_endpoint_quarantine_total 81
telemt_me_single_endpoint_shadow_rotate_total 93
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
telemt_desync_total 889
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 675
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 11
telemt_pool_force_close_total 279
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 3896
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3698
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3617
telemt_me_writer_teardown_success_total{mode="normal"} 3944
telemt_me_writer_teardown_noop_total 3896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.542202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 107923
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 2214783440 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 66407173540 (61.85 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 92393.6 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6765208
telemt_connections_bad_total 682983
telemt_connections_current 2538
telemt_connections_me_current 2538
telemt_handshake_timeouts_total 194253
telemt_upstream_connect_attempt_total 34948
telemt_upstream_connect_success_total 34808
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 34911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 1424
telemt_me_reconnect_success_total 728
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 2061446
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5168089
telemt_me_endpoint_quarantine_total 615
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_me_writers_active_current 48
telemt_desync_total 19801
telemt_desync_full_logged_total 6612
telemt_desync_suppressed_total 13189
telemt_desync_frames_bucket_total{bucket="1_2"} 4815
telemt_desync_frames_bucket_total{bucket="3_10"} 7218
telemt_desync_frames_bucket_total{bucket="gt_10"} 7768
telemt_pool_swap_total 102
telemt_pool_force_close_total 2794
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 31412
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28618
telemt_me_writer_teardown_success_total{mode="normal"} 32106
telemt_me_writer_teardown_noop_total 31414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63520
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.203529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63520
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5143577
telemt_user_connections_current{user="hello"} 2538
telemt_user_octets_from_client{user="hello"} 103875416032 (96.74 GB)
telemt_user_octets_to_client{user="hello"} 2414536157848 (2.20 TB)
telemt_user_unique_ips_current{user="hello"} 1019
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 92390.3 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5768494
telemt_connections_bad_total 547232
telemt_connections_current 2181
telemt_connections_me_current 2181
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162739
telemt_upstream_connect_attempt_total 51110
telemt_upstream_connect_success_total 50725
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 51051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_reconnect_attempts_total 5211
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2113722
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4532474
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 701
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
telemt_desync_total 18427
telemt_desync_full_logged_total 6234
telemt_desync_suppressed_total 12193
telemt_desync_frames_bucket_total{bucket="1_2"} 4578
telemt_desync_frames_bucket_total{bucket="3_10"} 6729
telemt_desync_frames_bucket_total{bucket="gt_10"} 7120
telemt_pool_swap_total 100
telemt_pool_force_close_total 2749
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30390
telemt_me_writer_removed_unexpected_total 923
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28313
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 221
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27641
telemt_me_writer_teardown_success_total{mode="normal"} 31355
telemt_me_writer_teardown_noop_total 30394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.353164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4536069
telemt_user_connections_current{user="hello"} 2181
telemt_user_octets_from_client{user="hello"} 87191795629 (81.20 GB)
telemt_user_octets_to_client{user="hello"} 1942804193840 (1.77 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 992
telemt_user_unique_ips_recent_window{user="hello"} 208
```