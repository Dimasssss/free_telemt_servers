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

# Server Metrics 2026-03-21 23:52:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 9989.2 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156659
telemt_connections_bad_total 11261
telemt_connections_current 676
telemt_connections_me_current 676
telemt_handshake_timeouts_total 8258
telemt_upstream_connect_attempt_total 4035
telemt_upstream_connect_success_total 4034
telemt_upstream_connect_attempts_per_request{bucket="1"} 4034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 32881
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128076
telemt_me_endpoint_quarantine_total 68
telemt_me_single_endpoint_shadow_rotate_total 86
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
telemt_desync_total 765
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 525
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 366
telemt_pool_swap_total 11
telemt_pool_force_close_total 278
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3580
telemt_me_writer_removed_unexpected_total 60
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3370
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3302
telemt_me_writer_teardown_success_total{mode="normal"} 3628
telemt_me_writer_teardown_noop_total 3580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7208
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.187810
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7208
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 127919
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 1553517828 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 46495378760 (43.30 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 23355.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668744
telemt_connections_bad_total 34270
telemt_connections_current 675
telemt_connections_me_current 675
telemt_handshake_timeouts_total 25527
telemt_upstream_connect_attempt_total 9884
telemt_upstream_connect_success_total 9711
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 9866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 835
telemt_me_reconnect_success_total 295
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 255
telemt_me_route_drop_no_conn_total 325860
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543098
telemt_me_endpoint_quarantine_total 204
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 187
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
telemt_me_writers_active_current 44
telemt_desync_total 2382
telemt_desync_full_logged_total 1365
telemt_desync_suppressed_total 1017
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 985
telemt_pool_swap_total 25
telemt_pool_force_close_total 703
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8693
telemt_me_writer_removed_unexpected_total 239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8176
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7990
telemt_me_writer_teardown_success_total{mode="normal"} 8935
telemt_me_writer_teardown_noop_total 8693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17628
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.371240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17628
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 542355
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 9127933696 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 188538982832 (175.59 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 98215.4 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7437660
telemt_connections_bad_total 590297
telemt_connections_current 2169
telemt_connections_me_current 2169
telemt_handshake_timeouts_total 241288
telemt_upstream_connect_attempt_total 35607
telemt_upstream_connect_success_total 35538
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1488
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 4497800
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6063618
telemt_me_endpoint_quarantine_total 618
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 728
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
telemt_me_writers_active_current 43
telemt_desync_total 25747
telemt_desync_full_logged_total 8505
telemt_desync_suppressed_total 17242
telemt_desync_frames_bucket_total{bucket="1_2"} 5524
telemt_desync_frames_bucket_total{bucket="3_10"} 10052
telemt_desync_frames_bucket_total{bucket="gt_10"} 10171
telemt_pool_swap_total 106
telemt_pool_force_close_total 3533
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 569
telemt_me_draining_writers_reap_progress_total 32426
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28893
telemt_me_writer_teardown_success_total{mode="normal"} 32724
telemt_me_writer_teardown_noop_total 32470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.438184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 569
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6056079
telemt_user_connections_current{user="hello"} 2169
telemt_user_octets_from_client{user="hello"} 103912560660 (96.78 GB)
telemt_user_octets_to_client{user="hello"} 1987641188804 (1.81 TB)
telemt_user_unique_ips_current{user="hello"} 1003
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 98216.7 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6116690
telemt_connections_bad_total 578132
telemt_connections_current 1535
telemt_connections_me_current 1535
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 202048
telemt_upstream_connect_attempt_total 39522
telemt_upstream_connect_success_total 39183
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 39362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1804
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 746
telemt_me_route_drop_no_conn_total 2170554
telemt_me_route_drop_channel_closed_total 254
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4580659
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22029
telemt_desync_full_logged_total 7449
telemt_desync_suppressed_total 14580
telemt_desync_frames_bucket_total{bucket="1_2"} 5307
telemt_desync_frames_bucket_total{bucket="3_10"} 8549
telemt_desync_frames_bucket_total{bucket="gt_10"} 8173
telemt_pool_swap_total 108
telemt_pool_force_close_total 3224
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30970
telemt_me_writer_removed_unexpected_total 720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28994
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27746
telemt_me_writer_teardown_success_total{mode="normal"} 31625
telemt_me_writer_teardown_noop_total 30976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62601
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.981550
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62601
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4522405
telemt_user_connections_current{user="hello"} 1535
telemt_user_octets_from_client{user="hello"} 137903738729 (128.43 GB)
telemt_user_octets_to_client{user="hello"} 2115788293127 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 98180.7 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6026250
telemt_connections_bad_total 540012
telemt_connections_current 1490
telemt_connections_me_current 1490
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 192659
telemt_upstream_connect_attempt_total 45993
telemt_upstream_connect_success_total 45685
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 818
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 2102765
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4500459
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 733
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_warm_current 35
telemt_desync_total 21885
telemt_desync_full_logged_total 7284
telemt_desync_suppressed_total 14601
telemt_desync_frames_bucket_total{bucket="1_2"} 5352
telemt_desync_frames_bucket_total{bucket="3_10"} 8378
telemt_desync_frames_bucket_total{bucket="gt_10"} 8155
telemt_pool_swap_total 105
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32445
telemt_me_writer_removed_unexpected_total 732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30476
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29349
telemt_me_writer_teardown_success_total{mode="normal"} 33186
telemt_me_writer_teardown_noop_total 32456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65642
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.455040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65642
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4501786
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 131545661083 (122.51 GB)
telemt_user_octets_to_client{user="hello"} 2062188897331 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 98220.2 (27h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19959504
telemt_connections_bad_total 1469704
telemt_connections_current 2116
telemt_connections_me_current 2116
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 576929
telemt_upstream_connect_attempt_total 189112
telemt_upstream_connect_success_total 171490
telemt_upstream_connect_fail_total 16035
telemt_upstream_connect_attempts_per_request{bucket="1"} 187525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8881
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16035
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64342
telemt_me_reconnect_success_total 2152
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 39446184
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16249915
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 766
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_warm_current 36
telemt_desync_total 31296
telemt_desync_full_logged_total 9308
telemt_desync_suppressed_total 21988
telemt_desync_frames_bucket_total{bucket="1_2"} 6825
telemt_desync_frames_bucket_total{bucket="3_10"} 13854
telemt_desync_frames_bucket_total{bucket="gt_10"} 10617
telemt_pool_swap_total 100
telemt_pool_force_close_total 3316
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 756
telemt_me_draining_writers_reap_progress_total 30448
telemt_me_writer_removed_unexpected_total 2007
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4191
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27999
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27132
telemt_me_writer_teardown_success_total{mode="normal"} 32190
telemt_me_writer_teardown_noop_total 30474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.172710
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 756
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 16377877
telemt_user_connections_current{user="hello"} 2116
telemt_user_octets_from_client{user="hello"} 185849551740 (173.09 GB)
telemt_user_octets_to_client{user="hello"} 1111095771818 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 98187.6 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5822739
telemt_connections_bad_total 547956
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120039
telemt_upstream_connect_attempt_total 54118
telemt_upstream_connect_success_total 53498
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 54027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_reconnect_attempts_total 68085
telemt_me_reconnect_success_total 1679
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 2355047
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4538522
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 734
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 27
telemt_desync_total 22946
telemt_desync_full_logged_total 8029
telemt_desync_suppressed_total 14917
telemt_desync_frames_bucket_total{bucket="1_2"} 4346
telemt_desync_frames_bucket_total{bucket="3_10"} 8889
telemt_desync_frames_bucket_total{bucket="gt_10"} 9711
telemt_pool_swap_total 100
telemt_pool_force_close_total 2946
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 33808
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31742
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30862
telemt_me_writer_teardown_success_total{mode="normal"} 35335
telemt_me_writer_teardown_noop_total 33809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69144
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.922670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69144
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1423
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4531638
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 121747425728 (113.39 GB)
telemt_user_octets_to_client{user="hello"} 1851999341674 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35023.4 (9h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3696258
telemt_connections_bad_total 130910
telemt_connections_current 1297
telemt_connections_me_current 1297
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1540052
telemt_upstream_connect_attempt_total 22294
telemt_upstream_connect_success_total 22154
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 45583
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 993407
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1785097
telemt_me_endpoint_quarantine_total 243
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 262
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9916
telemt_desync_full_logged_total 3397
telemt_desync_suppressed_total 6519
telemt_desync_frames_bucket_total{bucket="1_2"} 1754
telemt_desync_frames_bucket_total{bucket="3_10"} 3794
telemt_desync_frames_bucket_total{bucket="gt_10"} 4368
telemt_pool_swap_total 37
telemt_pool_force_close_total 1225
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 11800
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11169
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10575
telemt_me_writer_teardown_success_total{mode="normal"} 12455
telemt_me_writer_teardown_noop_total 11802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24257
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.006437
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24257
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1788839
telemt_user_connections_current{user="hello"} 1297
telemt_user_octets_from_client{user="hello"} 52442736160 (48.84 GB)
telemt_user_octets_to_client{user="hello"} 766674886042 (714.02 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 15994.4 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157731
telemt_connections_bad_total 1396
telemt_connections_current 333
telemt_connections_me_current 333
telemt_handshake_timeouts_total 3781
telemt_upstream_connect_attempt_total 7303
telemt_upstream_connect_success_total 7284
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 156
telemt_me_reconnect_success_total 95
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 44644
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138381
telemt_me_endpoint_quarantine_total 139
telemt_me_single_endpoint_shadow_rotate_total 140
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
telemt_me_writers_active_current 45
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 17
telemt_pool_force_close_total 400
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6556
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6226
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6156
telemt_me_writer_teardown_success_total{mode="normal"} 6651
telemt_me_writer_teardown_noop_total 6556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.778814
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 87
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 138150
telemt_user_connections_current{user="hello"} 333
telemt_user_octets_from_client{user="hello"} 2553775792 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 80620315596 (75.08 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 98192.1 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7008974
telemt_connections_bad_total 711118
telemt_connections_current 1819
telemt_connections_me_current 1819
telemt_handshake_timeouts_total 199439
telemt_upstream_connect_attempt_total 37551
telemt_upstream_connect_success_total 37404
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 780
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 757
telemt_me_route_drop_no_conn_total 2095243
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5301102
telemt_me_endpoint_quarantine_total 667
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 750
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 40
telemt_desync_total 20476
telemt_desync_full_logged_total 6832
telemt_desync_suppressed_total 13644
telemt_desync_frames_bucket_total{bucket="1_2"} 5000
telemt_desync_frames_bucket_total{bucket="3_10"} 7421
telemt_desync_frames_bucket_total{bucket="gt_10"} 8055
telemt_pool_swap_total 108
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33755
telemt_me_writer_removed_unexpected_total 733
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31780
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30810
telemt_me_writer_teardown_success_total{mode="normal"} 34502
telemt_me_writer_teardown_noop_total 33757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.557657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5276330
telemt_user_connections_current{user="hello"} 1819
telemt_user_octets_from_client{user="hello"} 106698249048 (99.37 GB)
telemt_user_octets_to_client{user="hello"} 2480394371648 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 815
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 98188.7 (27h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6005705
telemt_connections_bad_total 589067
telemt_connections_current 1652
telemt_connections_me_current 1652
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 167092
telemt_upstream_connect_attempt_total 53576
telemt_upstream_connect_success_total 53170
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 53517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_reconnect_attempts_total 5297
telemt_me_reconnect_success_total 1088
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2148542
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4671084
telemt_me_endpoint_quarantine_total 773
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 746
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 32
telemt_desync_total 19264
telemt_desync_full_logged_total 6460
telemt_desync_suppressed_total 12804
telemt_desync_frames_bucket_total{bucket="1_2"} 4848
telemt_desync_frames_bucket_total{bucket="3_10"} 7007
telemt_desync_frames_bucket_total{bucket="gt_10"} 7409
telemt_pool_swap_total 106
telemt_pool_force_close_total 2908
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 365
telemt_me_draining_writers_reap_progress_total 32560
telemt_me_writer_removed_unexpected_total 977
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30379
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29652
telemt_me_writer_teardown_success_total{mode="normal"} 33581
telemt_me_writer_teardown_noop_total 32564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.860543
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 365
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 843
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 4674390
telemt_user_connections_current{user="hello"} 1652
telemt_user_octets_from_client{user="hello"} 88579253273 (82.50 GB)
telemt_user_octets_to_client{user="hello"} 2007333808892 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 755
telemt_user_unique_ips_recent_window{user="hello"} 163
```