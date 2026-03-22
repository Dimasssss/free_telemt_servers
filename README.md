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

# Server Metrics 2026-03-22 10:26:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47974.4 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1273272
telemt_connections_bad_total 67075
telemt_connections_current 1643
telemt_connections_me_current 1643
telemt_handshake_timeouts_total 58480
telemt_upstream_connect_attempt_total 18608
telemt_upstream_connect_success_total 18607
telemt_upstream_connect_attempts_per_request{bucket="1"} 18607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 555
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 698451
telemt_me_route_drop_channel_closed_total 320
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1063439
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_shadow_rotate_total 388
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 7093
telemt_desync_full_logged_total 2073
telemt_desync_suppressed_total 5020
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 2681
telemt_desync_frames_bucket_total{bucket="gt_10"} 2340
telemt_pool_swap_total 53
telemt_pool_force_close_total 1545
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 16955
telemt_me_writer_removed_unexpected_total 281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1174
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 33
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15410
telemt_me_writer_teardown_success_total{mode="normal"} 17155
telemt_me_writer_teardown_noop_total 16957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.469604
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34112
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1061536
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 17032806736 (15.86 GB)
telemt_user_octets_to_client{user="hello"} 335945088280 (312.87 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 61340.7 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2039489
telemt_connections_bad_total 173163
telemt_connections_current 2178
telemt_connections_me_current 2178
telemt_handshake_timeouts_total 49537
telemt_upstream_connect_attempt_total 36254
telemt_upstream_connect_success_total 35763
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 36194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3152
telemt_me_reconnect_success_total 1401
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 1473395
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1592318
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 483
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
telemt_me_writers_warm_current 34
telemt_desync_total 6638
telemt_desync_full_logged_total 3762
telemt_desync_suppressed_total 2876
telemt_desync_frames_bucket_total{bucket="1_2"} 1502
telemt_desync_frames_bucket_total{bucket="3_10"} 2597
telemt_desync_frames_bucket_total{bucket="gt_10"} 2539
telemt_pool_swap_total 61
telemt_pool_force_close_total 1725
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 24747
telemt_me_writer_removed_unexpected_total 1260
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23304
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23022
telemt_me_writer_teardown_success_total{mode="normal"} 26001
telemt_me_writer_teardown_noop_total 24747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50748
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.419245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50748
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1170
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1598369
telemt_user_connections_current{user="hello"} 2178
telemt_user_octets_from_client{user="hello"} 22157468794 (20.64 GB)
telemt_user_octets_to_client{user="hello"} 451083086348 (420.10 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1327
telemt_user_unique_ips_recent_window{user="hello"} 871
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 136200.7 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11205184
telemt_connections_bad_total 961042
telemt_connections_current 4916
telemt_connections_me_current 4916
telemt_handshake_timeouts_total 309837
telemt_upstream_connect_attempt_total 49815
telemt_upstream_connect_success_total 49735
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2131
telemt_me_reconnect_success_total 1093
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1075
telemt_me_route_drop_no_conn_total 7869037
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8897842
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1016
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
telemt_desync_total 37397
telemt_desync_full_logged_total 12115
telemt_desync_suppressed_total 25282
telemt_desync_frames_bucket_total{bucket="1_2"} 8424
telemt_desync_frames_bucket_total{bucket="3_10"} 14508
telemt_desync_frames_bucket_total{bucket="gt_10"} 14465
telemt_pool_swap_total 147
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 766
telemt_me_draining_writers_reap_progress_total 45451
telemt_me_writer_removed_unexpected_total 1034
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42028
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 333
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40509
telemt_me_writer_teardown_success_total{mode="normal"} 45909
telemt_me_writer_teardown_noop_total 45495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91404
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.649938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91404
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 766
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 8887171
telemt_user_connections_current{user="hello"} 4916
telemt_user_octets_from_client{user="hello"} 139383987504 (129.81 GB)
telemt_user_octets_to_client{user="hello"} 2693907896596 (2.45 TB)
telemt_user_unique_ips_current{user="hello"} 1778
telemt_user_unique_ips_recent_window{user="hello"} 1067
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 136206.1 (37h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8805609
telemt_connections_bad_total 788179
telemt_connections_current 5227
telemt_connections_me_current 5227
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 270900
telemt_upstream_connect_attempt_total 56090
telemt_upstream_connect_success_total 55535
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 55795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 3080
telemt_me_reconnect_success_total 1233
telemt_me_reader_eof_total 1122
telemt_me_idle_close_by_peer_total 1122
telemt_me_route_drop_no_conn_total 3490364
telemt_me_route_drop_channel_closed_total 361
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6549157
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1048
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
telemt_me_writers_active_current 85
telemt_desync_total 29543
telemt_desync_full_logged_total 10030
telemt_desync_suppressed_total 19513
telemt_desync_frames_bucket_total{bucket="1_2"} 7149
telemt_desync_frames_bucket_total{bucket="3_10"} 11409
telemt_desync_frames_bucket_total{bucket="gt_10"} 10985
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 43730
telemt_me_writer_removed_unexpected_total 1157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39269
telemt_me_writer_teardown_success_total{mode="normal"} 44781
telemt_me_writer_teardown_noop_total 43736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.336761
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6471081
telemt_user_connections_current{user="hello"} 5227
telemt_user_octets_from_client{user="hello"} 170823187823 (159.09 GB)
telemt_user_octets_to_client{user="hello"} 2994432281994 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1875
telemt_user_unique_ips_recent_window{user="hello"} 1088
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 136166.0 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8362135
telemt_connections_bad_total 699779
telemt_connections_current 4065
telemt_connections_me_current 4065
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 270421
telemt_upstream_connect_attempt_total 60591
telemt_upstream_connect_success_total 59891
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3526
telemt_me_reconnect_success_total 1478
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 3518119
telemt_me_route_drop_channel_closed_total 233
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6264152
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 998
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29030
telemt_desync_full_logged_total 9874
telemt_desync_suppressed_total 19156
telemt_desync_frames_bucket_total{bucket="1_2"} 6998
telemt_desync_frames_bucket_total{bucket="3_10"} 11186
telemt_desync_frames_bucket_total{bucket="gt_10"} 10846
telemt_pool_swap_total 144
telemt_pool_force_close_total 4394
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44741
telemt_me_writer_removed_unexpected_total 1387
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4201
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41874
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40347
telemt_me_writer_teardown_success_total{mode="normal"} 46075
telemt_me_writer_teardown_noop_total 44758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90833
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.316268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90833
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1299
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6255943
telemt_user_connections_current{user="hello"} 4065
telemt_user_octets_from_client{user="hello"} 156097782387 (145.38 GB)
telemt_user_octets_to_client{user="hello"} 2727149720583 (2.48 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6446.0 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755763
telemt_connections_bad_total 193199
telemt_connections_current 6127
telemt_connections_me_current 6127
telemt_handshake_timeouts_total 38185
telemt_upstream_connect_attempt_total 8994
telemt_upstream_connect_success_total 8519
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 8864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2706
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 135
telemt_me_idle_close_by_peer_total 135
telemt_me_route_drop_no_conn_total 6368319
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2299887
telemt_me_endpoint_quarantine_total 39
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 51
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
telemt_me_writers_active_current 41
telemt_desync_total 3563
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 2657
telemt_desync_frames_bucket_total{bucket="1_2"} 602
telemt_desync_frames_bucket_total{bucket="3_10"} 1404
telemt_desync_frames_bucket_total{bucket="gt_10"} 1557
telemt_pool_swap_total 5
telemt_pool_force_close_total 208
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 1733
telemt_me_writer_removed_unexpected_total 179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1591
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1525
telemt_me_writer_teardown_success_total{mode="normal"} 1897
telemt_me_writer_teardown_noop_total 1734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3631
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.724748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3631
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 135
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2304791
telemt_user_connections_current{user="hello"} 6127
telemt_user_octets_from_client{user="hello"} 12258566542 (11.42 GB)
telemt_user_octets_to_client{user="hello"} 66737906875 (62.15 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2135
telemt_user_unique_ips_recent_window{user="hello"} 2206
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 136172.9 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8028292
telemt_connections_bad_total 698168
telemt_connections_current 3630
telemt_connections_me_current 3630
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 163496
telemt_upstream_connect_attempt_total 85845
telemt_upstream_connect_success_total 84992
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 85725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70628
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1906
telemt_me_route_drop_no_conn_total 3487643
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6338194
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1025
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
telemt_me_writers_active_current 45
telemt_desync_total 32062
telemt_desync_full_logged_total 11056
telemt_desync_suppressed_total 21006
telemt_desync_frames_bucket_total{bucket="1_2"} 6516
telemt_desync_frames_bucket_total{bucket="3_10"} 12338
telemt_desync_frames_bucket_total{bucket="gt_10"} 13208
telemt_pool_swap_total 141
telemt_pool_force_close_total 4096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 47070
telemt_me_writer_removed_unexpected_total 1936
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44166
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3569
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 527
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42974
telemt_me_writer_teardown_success_total{mode="normal"} 49031
telemt_me_writer_teardown_noop_total 47071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96102
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.440530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96102
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1803
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6341878
telemt_user_connections_current{user="hello"} 3630
telemt_user_octets_from_client{user="hello"} 154452574943 (143.85 GB)
telemt_user_octets_to_client{user="hello"} 2532825796565 (2.30 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1294
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 73008.9 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6978467
telemt_connections_bad_total 262944
telemt_connections_current 5199
telemt_connections_me_current 5199
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2842781
telemt_upstream_connect_attempt_total 38361
telemt_upstream_connect_success_total 38082
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 38354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 47622
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 2100112
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3464758
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 554
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 88
telemt_me_writers_warm_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18593
telemt_desync_full_logged_total 6244
telemt_desync_suppressed_total 12349
telemt_desync_frames_bucket_total{bucket="1_2"} 3784
telemt_desync_frames_bucket_total{bucket="3_10"} 7123
telemt_desync_frames_bucket_total{bucket="gt_10"} 7686
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 26089
telemt_me_writer_removed_unexpected_total 1051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24854
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23779
telemt_me_writer_teardown_success_total{mode="normal"} 27163
telemt_me_writer_teardown_noop_total 26095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.911883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3464325
telemt_user_connections_current{user="hello"} 5199
telemt_user_octets_from_client{user="hello"} 83050331608 (77.35 GB)
telemt_user_octets_to_client{user="hello"} 1423652161578 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2162
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53980.0 (14h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543805
telemt_connections_bad_total 3802
telemt_connections_current 997
telemt_connections_me_current 997
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10165
telemt_upstream_connect_attempt_total 28203
telemt_upstream_connect_success_total 28138
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1155
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 178045
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491945
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 458
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 2467
telemt_desync_full_logged_total 707
telemt_desync_suppressed_total 1760
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 788
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 22865
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21661
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21511
telemt_me_writer_teardown_success_total{mode="normal"} 23325
telemt_me_writer_teardown_noop_total 22865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.434382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 493905
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 9708559629 (9.04 GB)
telemt_user_octets_to_client{user="hello"} 237453766239 (221.15 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 359
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 136177.2 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9779871
telemt_connections_bad_total 1141064
telemt_connections_current 5521
telemt_connections_me_current 5521
telemt_handshake_timeouts_total 263013
telemt_upstream_connect_attempt_total 52368
telemt_upstream_connect_success_total 52168
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2020
telemt_me_reconnect_success_total 1078
telemt_me_reader_eof_total 1047
telemt_me_idle_close_by_peer_total 1047
telemt_me_route_drop_no_conn_total 2802245
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7281640
telemt_me_endpoint_quarantine_total 962
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1030
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
telemt_me_writers_active_current 41
telemt_desync_total 29563
telemt_desync_full_logged_total 9689
telemt_desync_suppressed_total 19874
telemt_desync_frames_bucket_total{bucket="1_2"} 7282
telemt_desync_frames_bucket_total{bucket="3_10"} 10819
telemt_desync_frames_bucket_total{bucket="gt_10"} 11462
telemt_pool_swap_total 151
telemt_pool_force_close_total 4088
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 47236
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44462
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43148
telemt_me_writer_teardown_success_total{mode="normal"} 48274
telemt_me_writer_teardown_noop_total 47238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.047246
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 945
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7253666
telemt_user_connections_current{user="hello"} 5521
telemt_user_octets_from_client{user="hello"} 140227785892 (130.60 GB)
telemt_user_octets_to_client{user="hello"} 3379690734312 (3.07 TB)
telemt_user_unique_ips_current{user="hello"} 2056
telemt_user_unique_ips_recent_window{user="hello"} 761
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 136173.9 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8498619
telemt_connections_bad_total 949264
telemt_connections_current 4563
telemt_connections_me_current 4563
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 220247
telemt_upstream_connect_attempt_total 76874
telemt_upstream_connect_success_total 76327
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 76805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_reconnect_attempts_total 6587
telemt_me_reconnect_success_total 1546
telemt_me_reader_eof_total 1371
telemt_me_idle_close_by_peer_total 1371
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3039014
telemt_me_route_drop_channel_closed_total 266
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6496685
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1033
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
telemt_me_writers_active_current 43
telemt_desync_total 28689
telemt_desync_full_logged_total 9468
telemt_desync_suppressed_total 19221
telemt_desync_frames_bucket_total{bucket="1_2"} 7088
telemt_desync_frames_bucket_total{bucket="3_10"} 10569
telemt_desync_frames_bucket_total{bucket="gt_10"} 11032
telemt_pool_swap_total 148
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 45915
telemt_me_writer_removed_unexpected_total 1389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42904
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41897
telemt_me_writer_teardown_success_total{mode="normal"} 47367
telemt_me_writer_teardown_noop_total 45919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93286
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.617675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93286
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1203
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6504746
telemt_user_connections_current{user="hello"} 4563
telemt_user_octets_from_client{user="hello"} 117896564373 (109.80 GB)
telemt_user_octets_to_client{user="hello"} 2742890751955 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1690
telemt_user_unique_ips_recent_window{user="hello"} 670
```