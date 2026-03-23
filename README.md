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

# Server Metrics 2026-03-23 00:25:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 98326.4 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3459184
telemt_connections_bad_total 296761
telemt_connections_current 756
telemt_connections_me_current 756
telemt_handshake_timeouts_total 108250
telemt_upstream_connect_attempt_total 36436
telemt_upstream_connect_success_total 36435
telemt_upstream_connect_attempts_per_request{bucket="1"} 36435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1377
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 600
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 2977054
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2865950
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 765
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
telemt_desync_total 12349
telemt_desync_full_logged_total 3862
telemt_desync_suppressed_total 8487
telemt_desync_frames_bucket_total{bucket="1_2"} 3335
telemt_desync_frames_bucket_total{bucket="3_10"} 4492
telemt_desync_frames_bucket_total{bucket="gt_10"} 4522
telemt_pool_swap_total 109
telemt_pool_force_close_total 3375
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 33379
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30004
telemt_me_writer_teardown_success_total{mode="normal"} 33605
telemt_me_writer_teardown_noop_total 33390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66995
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.103977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66995
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2855151
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 40850111056 (38.04 GB)
telemt_user_octets_to_client{user="hello"} 781744299368 (728.06 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 111692.6 (31h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3985428
telemt_connections_bad_total 364394
telemt_connections_current 457
telemt_connections_me_current 457
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100400
telemt_upstream_connect_attempt_total 69014
telemt_upstream_connect_success_total 68180
telemt_upstream_connect_fail_total 740
telemt_upstream_connect_attempts_per_request{bucket="1"} 68920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 740
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9812
telemt_me_reconnect_success_total 3555
telemt_me_reader_eof_total 3561
telemt_me_idle_close_by_peer_total 3561
telemt_me_route_drop_no_conn_total 3639701
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3169100
telemt_me_endpoint_quarantine_total 858
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 868
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 24
telemt_desync_total 12924
telemt_desync_full_logged_total 7244
telemt_desync_suppressed_total 5680
telemt_desync_frames_bucket_total{bucket="1_2"} 2934
telemt_desync_frames_bucket_total{bucket="3_10"} 5064
telemt_desync_frames_bucket_total{bucket="gt_10"} 4926
telemt_pool_swap_total 103
telemt_pool_force_close_total 3031
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 45552
telemt_me_writer_removed_unexpected_total 3493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42521
telemt_me_writer_teardown_success_total{mode="normal"} 49076
telemt_me_writer_teardown_noop_total 45553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94629
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.569526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94629
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3193
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3181581
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 42936723186 (39.99 GB)
telemt_user_octets_to_client{user="hello"} 789111536036 (734.92 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 186552.4 (51h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16304762
telemt_connections_bad_total 1642797
telemt_connections_current 663
telemt_connections_me_current 663
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396937
telemt_upstream_connect_attempt_total 83372
telemt_upstream_connect_success_total 83269
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 83286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1713
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2976
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1502
telemt_me_idle_close_by_peer_total 1500
telemt_me_route_drop_no_conn_total 14041613
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12951235
telemt_me_endpoint_quarantine_total 1227
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1402
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53660
telemt_desync_full_logged_total 17021
telemt_desync_suppressed_total 36639
telemt_desync_frames_bucket_total{bucket="1_2"} 11950
telemt_desync_frames_bucket_total{bucket="3_10"} 20923
telemt_desync_frames_bucket_total{bucket="gt_10"} 20787
telemt_pool_swap_total 202
telemt_pool_force_close_total 6661
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1057
telemt_me_draining_writers_reap_progress_total 62920
telemt_me_writer_removed_unexpected_total 1447
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58234
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6191
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56259
telemt_me_writer_teardown_success_total{mode="normal"} 63641
telemt_me_writer_teardown_noop_total 62973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.573911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1057
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1344
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12951293
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 190933372549 (177.82 GB)
telemt_user_octets_to_client{user="hello"} 3483281318487 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 186553.8 (51h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11845241
telemt_connections_bad_total 1226422
telemt_connections_current 566
telemt_connections_me_current 566
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344443
telemt_upstream_connect_attempt_total 97717
telemt_upstream_connect_success_total 96398
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 97264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3800
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4390
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1724
telemt_me_idle_close_by_peer_total 1724
telemt_me_route_drop_no_conn_total 4552208
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8798178
telemt_me_endpoint_quarantine_total 1233
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1422
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38700
telemt_desync_full_logged_total 13026
telemt_desync_suppressed_total 25674
telemt_desync_frames_bucket_total{bucket="1_2"} 9588
telemt_desync_frames_bucket_total{bucket="3_10"} 14863
telemt_desync_frames_bucket_total{bucket="gt_10"} 14249
telemt_pool_swap_total 199
telemt_pool_force_close_total 6022
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 61123
telemt_me_writer_removed_unexpected_total 1755
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5506
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5510
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55101
telemt_me_writer_teardown_success_total{mode="normal"} 62733
telemt_me_writer_teardown_noop_total 61148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.390668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1587
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8735946
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 217678127480 (202.73 GB)
telemt_user_octets_to_client{user="hello"} 3955198643027 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 186518.0 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11034089
telemt_connections_bad_total 971536
telemt_connections_current 405
telemt_connections_me_current 405
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345443
telemt_upstream_connect_attempt_total 81995
telemt_upstream_connect_success_total 80437
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5706
telemt_me_reconnect_success_total 2348
telemt_me_reader_eof_total 2091
telemt_me_idle_close_by_peer_total 2090
telemt_me_route_drop_no_conn_total 5334126
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8341661
telemt_me_endpoint_quarantine_total 1308
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38018
telemt_desync_full_logged_total 12605
telemt_desync_suppressed_total 25413
telemt_desync_frames_bucket_total{bucket="1_2"} 9601
telemt_desync_frames_bucket_total{bucket="3_10"} 14543
telemt_desync_frames_bucket_total{bucket="gt_10"} 13874
telemt_pool_swap_total 195
telemt_pool_force_close_total 5922
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 61496
telemt_me_writer_removed_unexpected_total 2242
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5351
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55574
telemt_me_writer_teardown_success_total{mode="normal"} 63669
telemt_me_writer_teardown_noop_total 61567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.685289
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2038
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8333631
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 192570507523 (179.35 GB)
telemt_user_octets_to_client{user="hello"} 3464124145785 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 56797.9 (15h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11201156
telemt_connections_bad_total 668585
telemt_connections_current 1006
telemt_connections_me_current 1006
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 266701
telemt_upstream_connect_attempt_total 55938
telemt_upstream_connect_success_total 53073
telemt_upstream_connect_fail_total 1907
telemt_upstream_connect_attempts_per_request{bucket="1"} 54980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27384
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1907
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7471
telemt_me_reconnect_success_total 1168
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 25280556
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9300308
telemt_me_endpoint_quarantine_total 412
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 446
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 36
telemt_desync_total 16267
telemt_desync_full_logged_total 4417
telemt_desync_suppressed_total 11850
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 6613
telemt_desync_frames_bucket_total{bucket="gt_10"} 6568
telemt_pool_swap_total 58
telemt_pool_force_close_total 1936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 17493
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16114
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1629
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15557
telemt_me_writer_teardown_success_total{mode="normal"} 18492
telemt_me_writer_teardown_noop_total 17512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36004
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.566279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36004
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9325762
telemt_user_connections_current{user="hello"} 1006
telemt_user_octets_from_client{user="hello"} 86854645942 (80.89 GB)
telemt_user_octets_to_client{user="hello"} 600157569753 (558.94 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 186524.6 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10967268
telemt_connections_bad_total 942503
telemt_connections_current 515
telemt_connections_me_current 515
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241818
telemt_upstream_connect_attempt_total 110927
telemt_upstream_connect_success_total 109781
telemt_upstream_connect_fail_total 973
telemt_upstream_connect_attempts_per_request{bucket="1"} 110754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 973
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72858
telemt_me_reconnect_success_total 3053
telemt_me_reader_eof_total 2740
telemt_me_idle_close_by_peer_total 2738
telemt_me_route_drop_no_conn_total 5257630
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8656572
telemt_me_endpoint_quarantine_total 1254
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1406
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 46158
telemt_desync_full_logged_total 15801
telemt_desync_suppressed_total 30357
telemt_desync_frames_bucket_total{bucket="1_2"} 9375
telemt_desync_frames_bucket_total{bucket="3_10"} 17669
telemt_desync_frames_bucket_total{bucket="gt_10"} 19114
telemt_pool_swap_total 191
telemt_pool_force_close_total 5627
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65689
telemt_me_writer_removed_unexpected_total 2770
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61727
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4878
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60062
telemt_me_writer_teardown_success_total{mode="normal"} 68493
telemt_me_writer_teardown_noop_total 65690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.227372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2577
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8659604
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 194428879917 (181.08 GB)
telemt_user_octets_to_client{user="hello"} 3306745854356 (3.01 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 123360.9 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11664266
telemt_connections_bad_total 476692
telemt_connections_current 670
telemt_connections_me_current 670
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759537
telemt_upstream_connect_attempt_total 59112
telemt_upstream_connect_success_total 58681
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 59101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_reconnect_attempts_total 48860
telemt_me_reconnect_success_total 1790
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1460
telemt_me_route_drop_no_conn_total 4083777
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5604302
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 941
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 17
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31490
telemt_desync_full_logged_total 10731
telemt_desync_suppressed_total 20759
telemt_desync_frames_bucket_total{bucket="1_2"} 6270
telemt_desync_frames_bucket_total{bucket="3_10"} 12417
telemt_desync_frames_bucket_total{bucket="gt_10"} 12803
telemt_pool_swap_total 130
telemt_pool_force_close_total 3842
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 44778
telemt_me_writer_removed_unexpected_total 1512
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3716
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42617
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40936
telemt_me_writer_teardown_success_total{mode="normal"} 46333
telemt_me_writer_teardown_noop_total 44785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.679068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2735
telemt_me_writer_restored_same_endpoint_total 1591
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5596875
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 118968066660 (110.80 GB)
telemt_user_octets_to_client{user="hello"} 2165476873438 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 104331.4 (28h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1506921
telemt_connections_bad_total 36683
telemt_connections_current 415
telemt_connections_me_current 415
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30200
telemt_upstream_connect_attempt_total 48870
telemt_upstream_connect_success_total 48715
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 48842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 785
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2207
telemt_me_reconnect_success_total 891
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 515358
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1338913
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 860
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 42
telemt_desync_total 8750
telemt_desync_full_logged_total 2582
telemt_desync_suppressed_total 6168
telemt_desync_frames_bucket_total{bucket="1_2"} 2385
telemt_desync_frames_bucket_total{bucket="3_10"} 3355
telemt_desync_frames_bucket_total{bucket="gt_10"} 3010
telemt_pool_swap_total 112
telemt_pool_force_close_total 2892
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 41224
telemt_me_writer_removed_unexpected_total 845
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2804
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38332
telemt_me_writer_teardown_success_total{mode="normal"} 42106
telemt_me_writer_teardown_noop_total 41228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.196982
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1334738
telemt_user_connections_current{user="hello"} 415
telemt_user_octets_from_client{user="hello"} 25834456297 (24.06 GB)
telemt_user_octets_to_client{user="hello"} 572001002331 (532.72 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 186529.1 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13305738
telemt_connections_bad_total 1599915
telemt_connections_current 588
telemt_connections_me_current 588
telemt_handshake_timeouts_total 387928
telemt_upstream_connect_attempt_total 72843
telemt_upstream_connect_success_total 72496
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 72707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2922
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1443
telemt_me_route_drop_no_conn_total 4480362
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10032127
telemt_me_endpoint_quarantine_total 1310
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1407
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 41977
telemt_desync_full_logged_total 13707
telemt_desync_suppressed_total 28270
telemt_desync_frames_bucket_total{bucket="1_2"} 10137
telemt_desync_frames_bucket_total{bucket="3_10"} 15430
telemt_desync_frames_bucket_total{bucket="gt_10"} 16410
telemt_pool_swap_total 207
telemt_pool_force_close_total 5550
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 65798
telemt_me_writer_removed_unexpected_total 1381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5217
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62014
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60248
telemt_me_writer_teardown_success_total{mode="normal"} 67231
telemt_me_writer_teardown_noop_total 65800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133031
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.747824
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133031
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 9998847
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 194484063916 (181.13 GB)
telemt_user_octets_to_client{user="hello"} 4434196917888 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 186525.8 (51h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11610171
telemt_connections_bad_total 1348639
telemt_connections_current 483
telemt_connections_me_current 483
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 310475
telemt_upstream_connect_attempt_total 99568
telemt_upstream_connect_success_total 98687
telemt_upstream_connect_fail_total 673
telemt_upstream_connect_attempts_per_request{bucket="1"} 99360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 673
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10354
telemt_me_reconnect_success_total 2548
telemt_me_reader_eof_total 2364
telemt_me_idle_close_by_peer_total 2363
telemt_me_seq_mismatch_total 95
telemt_me_route_drop_no_conn_total 5647567
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8942032
telemt_me_endpoint_quarantine_total 1496
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1409
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 41702
telemt_desync_full_logged_total 13411
telemt_desync_suppressed_total 28291
telemt_desync_frames_bucket_total{bucket="1_2"} 10749
telemt_desync_frames_bucket_total{bucket="3_10"} 15332
telemt_desync_frames_bucket_total{bucket="gt_10"} 15621
telemt_pool_swap_total 197
telemt_pool_force_close_total 5343
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 662
telemt_me_draining_writers_reap_progress_total 65838
telemt_me_writer_removed_unexpected_total 2405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6573
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60495
telemt_me_writer_teardown_success_total{mode="normal"} 68326
telemt_me_writer_teardown_noop_total 65843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.448466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 662
telemt_me_refill_failed_total 404
telemt_me_writer_restored_same_endpoint_total 2056
telemt_me_writer_restored_fallback_total 130
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 8945920
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 157193797665 (146.40 GB)
telemt_user_octets_to_client{user="hello"} 3482741800631 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 155
```