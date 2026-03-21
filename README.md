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

# Server Metrics 2026-03-21 20:49:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87228.8 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3100147
telemt_connections_bad_total 180293
telemt_connections_current 897
telemt_connections_me_current 897
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 97060
telemt_upstream_connect_attempt_total 35595
telemt_upstream_connect_success_total 35446
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 35552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1932
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 738
telemt_me_idle_close_by_peer_total 738
telemt_me_route_drop_no_conn_total 2628527
telemt_me_route_drop_channel_closed_total 847
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2507774
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 590
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 679
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
telemt_desync_total 10023
telemt_desync_full_logged_total 3503
telemt_desync_suppressed_total 6520
telemt_desync_frames_bucket_total{bucket="1_2"} 2175
telemt_desync_frames_bucket_total{bucket="3_10"} 3751
telemt_desync_frames_bucket_total{bucket="gt_10"} 4097
telemt_pool_swap_total 94
telemt_pool_force_close_total 2844
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 29216
telemt_me_writer_removed_unexpected_total 720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2450
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27226
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2704
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26372
telemt_me_writer_teardown_success_total{mode="normal"} 29676
telemt_me_writer_teardown_noop_total 29224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.149325
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2507372
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 37137606053 (34.59 GB)
telemt_user_octets_to_client{user="hello"} 640300561342 (596.33 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 12366.7 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485624
telemt_connections_bad_total 22687
telemt_connections_current 1458
telemt_connections_me_current 1458
telemt_handshake_timeouts_total 17124
telemt_upstream_connect_attempt_total 4866
telemt_upstream_connect_success_total 4768
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 129
telemt_me_idle_close_by_peer_total 129
telemt_me_route_drop_no_conn_total 281222
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 394645
telemt_me_endpoint_quarantine_total 91
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 98
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
telemt_me_writers_active_current 45
telemt_desync_total 1693
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 726
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 702
telemt_pool_swap_total 13
telemt_pool_force_close_total 392
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 4225
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3981
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3833
telemt_me_writer_teardown_success_total{mode="normal"} 4341
telemt_me_writer_teardown_noop_total 4225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.243375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 394153
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 6483757724 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 120512618772 (112.24 GB)
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 87227.0 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6938772
telemt_connections_bad_total 537967
telemt_connections_current 3839
telemt_connections_me_current 3839
telemt_handshake_timeouts_total 216407
telemt_upstream_connect_attempt_total 31279
telemt_upstream_connect_success_total 31216
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 672
telemt_me_reader_eof_total 682
telemt_me_idle_close_by_peer_total 682
telemt_me_route_drop_no_conn_total 4374123
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5677090
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 646
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
telemt_me_writers_active_current 43
telemt_desync_total 23503
telemt_desync_full_logged_total 7813
telemt_desync_suppressed_total 15690
telemt_desync_frames_bucket_total{bucket="1_2"} 4910
telemt_desync_frames_bucket_total{bucket="3_10"} 9331
telemt_desync_frames_bucket_total{bucket="gt_10"} 9262
telemt_pool_swap_total 93
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 509
telemt_me_draining_writers_reap_progress_total 28469
telemt_me_writer_removed_unexpected_total 656
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2441
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2895
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25341
telemt_me_writer_teardown_success_total{mode="normal"} 28752
telemt_me_writer_teardown_noop_total 28506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 139.244953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 509
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 603
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 5670286
telemt_user_connections_current{user="hello"} 3839
telemt_user_octets_from_client{user="hello"} 97412353444 (90.72 GB)
telemt_user_octets_to_client{user="hello"} 1789364548960 (1.63 TB)
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 87227.6 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5621233
telemt_connections_bad_total 543106
telemt_connections_current 3017
telemt_connections_me_current 3017
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 184732
telemt_upstream_connect_attempt_total 35361
telemt_upstream_connect_success_total 35043
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1672
telemt_me_reconnect_success_total 698
telemt_me_reader_eof_total 672
telemt_me_idle_close_by_peer_total 672
telemt_me_route_drop_no_conn_total 1942162
telemt_me_route_drop_channel_closed_total 221
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4205558
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 663
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
telemt_me_writers_active_current 44
telemt_desync_total 20061
telemt_desync_full_logged_total 6654
telemt_desync_suppressed_total 13407
telemt_desync_frames_bucket_total{bucket="1_2"} 4911
telemt_desync_frames_bucket_total{bucket="3_10"} 7764
telemt_desync_frames_bucket_total{bucket="gt_10"} 7386
telemt_pool_swap_total 95
telemt_pool_force_close_total 2882
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 323
telemt_me_draining_writers_reap_progress_total 27238
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2687
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 195
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24356
telemt_me_writer_teardown_success_total{mode="normal"} 27818
telemt_me_writer_teardown_noop_total 27243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 44.958448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 323
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4198217
telemt_user_connections_current{user="hello"} 3017
telemt_user_octets_from_client{user="hello"} 126428225405 (117.75 GB)
telemt_user_octets_to_client{user="hello"} 1927263496419 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1232
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 87191.4 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5548272
telemt_connections_bad_total 499294
telemt_connections_current 2829
telemt_connections_me_current 2829
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 168834
telemt_upstream_connect_attempt_total 41808
telemt_upstream_connect_success_total 41538
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1731
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 1996980
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4190578
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 648
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
telemt_me_writers_active_current 44
telemt_desync_total 19804
telemt_desync_full_logged_total 6479
telemt_desync_suppressed_total 13325
telemt_desync_frames_bucket_total{bucket="1_2"} 4932
telemt_desync_frames_bucket_total{bucket="3_10"} 7503
telemt_desync_frames_bucket_total{bucket="gt_10"} 7369
telemt_pool_swap_total 93
telemt_pool_force_close_total 2747
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 28673
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26915
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2534
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25926
telemt_me_writer_teardown_success_total{mode="normal"} 29372
telemt_me_writer_teardown_noop_total 28683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.230670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4192686
telemt_user_connections_current{user="hello"} 2829
telemt_user_octets_from_client{user="hello"} 122347163239 (113.94 GB)
telemt_user_octets_to_client{user="hello"} 1915523746975 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1215
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 87230.6 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19167851
telemt_connections_bad_total 1248047
telemt_connections_current 3577
telemt_connections_me_current 3577
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 534816
telemt_upstream_connect_attempt_total 181238
telemt_upstream_connect_success_total 164005
telemt_upstream_connect_fail_total 15800
telemt_upstream_connect_attempts_per_request{bucket="1"} 179805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8847
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15800
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59592
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1206
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 39098551
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15758753
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 645
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 680
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
telemt_me_writers_active_current 43
telemt_desync_total 29474
telemt_desync_full_logged_total 8696
telemt_desync_suppressed_total 20778
telemt_desync_frames_bucket_total{bucket="1_2"} 6458
telemt_desync_frames_bucket_total{bucket="3_10"} 13052
telemt_desync_frames_bucket_total{bucket="gt_10"} 9964
telemt_pool_swap_total 89
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 26816
telemt_me_writer_removed_unexpected_total 1739
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23841
telemt_me_writer_teardown_success_total{mode="normal"} 28299
telemt_me_writer_teardown_noop_total 26842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.318143
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1274
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 15883964
telemt_user_connections_current{user="hello"} 3577
telemt_user_octets_from_client{user="hello"} 152328932094 (141.87 GB)
telemt_user_octets_to_client{user="hello"} 974788909470 (907.84 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1441
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 87198.0 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5443328
telemt_connections_bad_total 523710
telemt_connections_current 3231
telemt_connections_me_current 3231
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 112127
telemt_upstream_connect_attempt_total 44925
telemt_upstream_connect_success_total 44438
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 44841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 11069
telemt_me_reconnect_success_total 1269
telemt_me_reader_eof_total 1200
telemt_me_idle_close_by_peer_total 1200
telemt_me_route_drop_no_conn_total 2272714
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4228176
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 647
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
telemt_me_writers_active_current 46
telemt_desync_total 20975
telemt_desync_full_logged_total 7272
telemt_desync_suppressed_total 13703
telemt_desync_frames_bucket_total{bucket="1_2"} 4000
telemt_desync_frames_bucket_total{bucket="3_10"} 8170
telemt_desync_frames_bucket_total{bucket="gt_10"} 8805
telemt_pool_swap_total 88
telemt_pool_force_close_total 2605
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 29499
telemt_me_writer_removed_unexpected_total 1180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3002
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27690
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26894
telemt_me_writer_teardown_success_total{mode="normal"} 30692
telemt_me_writer_teardown_noop_total 29500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60192
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.364650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60192
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1075
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4217898
telemt_user_connections_current{user="hello"} 3231
telemt_user_octets_from_client{user="hello"} 112863993521 (105.11 GB)
telemt_user_octets_to_client{user="hello"} 1710651475359 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1268
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 24033.8 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3177985
telemt_connections_bad_total 117166
telemt_connections_current 2582
telemt_connections_me_current 2582
telemt_handshake_timeouts_total 1366824
telemt_upstream_connect_attempt_total 7792
telemt_upstream_connect_success_total 7686
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 7786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_reconnect_attempts_total 2206
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 207
telemt_me_idle_close_by_peer_total 207
telemt_me_route_drop_no_conn_total 918497
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1503960
telemt_me_endpoint_quarantine_total 121
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 178
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
telemt_me_writers_active_current 47
telemt_desync_total 8267
telemt_desync_full_logged_total 2755
telemt_desync_suppressed_total 5512
telemt_desync_frames_bucket_total{bucket="1_2"} 1480
telemt_desync_frames_bucket_total{bucket="3_10"} 3132
telemt_desync_frames_bucket_total{bucket="gt_10"} 3655
telemt_pool_swap_total 25
telemt_pool_force_close_total 815
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 6774
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 645
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5959
telemt_me_writer_teardown_success_total{mode="normal"} 7006
telemt_me_writer_teardown_noop_total 6775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13781
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.139398
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13781
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1499586
telemt_user_connections_current{user="hello"} 2582
telemt_user_octets_from_client{user="hello"} 44839443064 (41.76 GB)
telemt_user_octets_to_client{user="hello"} 624664440812 (581.76 GB)
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 356
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5005.1 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55648
telemt_connections_bad_total 173
telemt_connections_current 573
telemt_connections_me_current 573
telemt_handshake_timeouts_total 818
telemt_upstream_connect_attempt_total 2188
telemt_upstream_connect_success_total 2181
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 55
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 16216
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49012
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 46
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
telemt_desync_total 373
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 5
telemt_pool_force_close_total 134
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 1889
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1789
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1755
telemt_me_writer_teardown_success_total{mode="normal"} 1913
telemt_me_writer_teardown_noop_total 1889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3802
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.263434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3802
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 48931
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 1084602388 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 39376190748 (36.67 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 87202.6 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6467763
telemt_connections_bad_total 661271
telemt_connections_current 3257
telemt_connections_me_current 3257
telemt_handshake_timeouts_total 187020
telemt_upstream_connect_attempt_total 33002
telemt_upstream_connect_success_total 32871
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 703
telemt_me_reader_eof_total 678
telemt_me_idle_close_by_peer_total 678
telemt_me_route_drop_no_conn_total 1999574
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4958582
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 662
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
telemt_me_writers_active_current 45
telemt_desync_total 18889
telemt_desync_full_logged_total 6292
telemt_desync_suppressed_total 12597
telemt_desync_frames_bucket_total{bucket="1_2"} 4600
telemt_desync_frames_bucket_total{bucket="3_10"} 6881
telemt_desync_frames_bucket_total{bucket="gt_10"} 7408
telemt_pool_swap_total 96
telemt_pool_force_close_total 2624
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 329
telemt_me_draining_writers_reap_progress_total 29629
telemt_me_writer_removed_unexpected_total 661
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2402
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27895
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2540
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27005
telemt_me_writer_teardown_success_total{mode="normal"} 30297
telemt_me_writer_teardown_noop_total 29631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59928
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.722950
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59928
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 329
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 628
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4934429
telemt_user_connections_current{user="hello"} 3257
telemt_user_octets_from_client{user="hello"} 98479117944 (91.72 GB)
telemt_user_octets_to_client{user="hello"} 2304269380204 (2.10 TB)
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 87199.3 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5488146
telemt_connections_bad_total 513571
telemt_connections_current 3072
telemt_connections_me_current 3072
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 157109
telemt_upstream_connect_attempt_total 49430
telemt_upstream_connect_success_total 49065
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 49371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_reconnect_attempts_total 4483
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2054715
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4323179
telemt_me_endpoint_quarantine_total 688
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 660
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
telemt_desync_total 17564
telemt_desync_full_logged_total 5921
telemt_desync_suppressed_total 11643
telemt_desync_frames_bucket_total{bucket="1_2"} 4339
telemt_desync_frames_bucket_total{bucket="3_10"} 6453
telemt_desync_frames_bucket_total{bucket="gt_10"} 6772
telemt_pool_swap_total 94
telemt_pool_force_close_total 2552
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 28879
telemt_me_writer_removed_unexpected_total 892
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2890
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2358
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26327
telemt_me_writer_teardown_success_total{mode="normal"} 29810
telemt_me_writer_teardown_noop_total 28883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.940805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4327328
telemt_user_connections_current{user="hello"} 3072
telemt_user_octets_from_client{user="hello"} 83102735585 (77.40 GB)
telemt_user_octets_to_client{user="hello"} 1817143237056 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1238
telemt_user_unique_ips_recent_window{user="hello"} 380
```