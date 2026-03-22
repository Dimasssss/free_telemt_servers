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

# Server Metrics 2026-03-22 08:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42763.8 (11h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040463
telemt_connections_bad_total 58750
telemt_connections_current 1763
telemt_connections_me_current 1763
telemt_handshake_timeouts_total 47652
telemt_upstream_connect_attempt_total 16912
telemt_upstream_connect_success_total 16911
telemt_upstream_connect_attempts_per_request{bucket="1"} 16911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 259
telemt_me_idle_close_by_peer_total 259
telemt_me_route_drop_no_conn_total 568334
telemt_me_route_drop_channel_closed_total 194
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865809
telemt_me_endpoint_quarantine_total 303
telemt_me_single_endpoint_shadow_rotate_total 344
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
telemt_desync_total 6363
telemt_desync_full_logged_total 1796
telemt_desync_suppressed_total 4567
telemt_desync_frames_bucket_total{bucket="1_2"} 1912
telemt_desync_frames_bucket_total{bucket="3_10"} 2390
telemt_desync_frames_bucket_total{bucket="gt_10"} 2061
telemt_pool_swap_total 47
telemt_pool_force_close_total 1330
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 151
telemt_me_draining_writers_reap_progress_total 15362
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1061
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14508
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14032
telemt_me_writer_teardown_success_total{mode="normal"} 15569
telemt_me_writer_teardown_noop_total 15364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30933
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.613185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30933
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 151
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 864216
telemt_user_connections_current{user="hello"} 1763
telemt_user_octets_from_client{user="hello"} 12573112288 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 277817560544 (258.74 GB)
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 56129.9 (15h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1565257
telemt_connections_bad_total 153449
telemt_connections_current 980
telemt_connections_me_current 980
telemt_handshake_timeouts_total 43429
telemt_upstream_connect_attempt_total 33826
telemt_upstream_connect_success_total 33389
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 33771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2505
telemt_me_reconnect_success_total 1075
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 976
telemt_me_route_drop_no_conn_total 738176
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1180495
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_me_writers_active_current 43
telemt_desync_total 5276
telemt_desync_full_logged_total 3049
telemt_desync_suppressed_total 2227
telemt_desync_frames_bucket_total{bucket="1_2"} 1161
telemt_desync_frames_bucket_total{bucket="3_10"} 2044
telemt_desync_frames_bucket_total{bucket="gt_10"} 2071
telemt_pool_swap_total 58
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 22881
telemt_me_writer_removed_unexpected_total 944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21547
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21300
telemt_me_writer_teardown_success_total{mode="normal"} 23816
telemt_me_writer_teardown_noop_total 22881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.122848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1186673
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 18063203210 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 399541497472 (372.10 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 599
telemt_user_unique_ips_recent_window{user="hello"} 452
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 130989.8 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9964908
telemt_connections_bad_total 885696
telemt_connections_current 4631
telemt_connections_me_current 4631
telemt_handshake_timeouts_total 294923
telemt_upstream_connect_attempt_total 48234
telemt_upstream_connect_success_total 48154
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1944
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 1003
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 5779174
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7831919
telemt_me_endpoint_quarantine_total 820
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 980
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
telemt_desync_total 33934
telemt_desync_full_logged_total 11110
telemt_desync_suppressed_total 22824
telemt_desync_frames_bucket_total{bucket="1_2"} 7477
telemt_desync_frames_bucket_total{bucket="3_10"} 13219
telemt_desync_frames_bucket_total{bucket="gt_10"} 13238
telemt_pool_swap_total 141
telemt_pool_force_close_total 4712
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 718
telemt_me_draining_writers_reap_progress_total 44038
telemt_me_writer_removed_unexpected_total 964
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3703
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4397
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39326
telemt_me_writer_teardown_success_total{mode="normal"} 44458
telemt_me_writer_teardown_noop_total 44082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 191.297953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 718
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 890
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 7821966
telemt_user_connections_current{user="hello"} 4631
telemt_user_octets_from_client{user="hello"} 127968791532 (119.18 GB)
telemt_user_octets_to_client{user="hello"} 2577661352168 (2.34 TB)
telemt_user_unique_ips_current{user="hello"} 1861
telemt_user_unique_ips_recent_window{user="hello"} 677
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 130991.2 (36h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8086682
telemt_connections_bad_total 726218
telemt_connections_current 3841
telemt_connections_me_current 3841
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 258460
telemt_upstream_connect_attempt_total 54240
telemt_upstream_connect_success_total 53762
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 54008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2923
telemt_me_reconnect_success_total 1097
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2703418
telemt_me_route_drop_channel_closed_total 322
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5975847
telemt_me_endpoint_quarantine_total 831
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1009
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
telemt_me_writers_active_current 46
telemt_desync_total 27507
telemt_desync_full_logged_total 9349
telemt_desync_suppressed_total 18158
telemt_desync_frames_bucket_total{bucket="1_2"} 6639
telemt_desync_frames_bucket_total{bucket="3_10"} 10644
telemt_desync_frames_bucket_total{bucket="gt_10"} 10224
telemt_pool_swap_total 143
telemt_pool_force_close_total 4301
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 42246
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3608
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 254
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37945
telemt_me_writer_teardown_success_total{mode="normal"} 43173
telemt_me_writer_teardown_noop_total 42252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85425
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 60.076154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85425
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5898313
telemt_user_connections_current{user="hello"} 3841
telemt_user_octets_from_client{user="hello"} 162684737471 (151.51 GB)
telemt_user_octets_to_client{user="hello"} 2831064302822 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1538
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 130956.6 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7758250
telemt_connections_bad_total 643810
telemt_connections_current 4171
telemt_connections_me_current 4171
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 257621
telemt_upstream_connect_attempt_total 58719
telemt_upstream_connect_success_total 58037
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1320
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2895
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1167
telemt_me_idle_close_by_peer_total 1167
telemt_me_route_drop_no_conn_total 3123607
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5787917
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 965
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
telemt_me_writers_active_current 85
telemt_desync_total 27129
telemt_desync_full_logged_total 9246
telemt_desync_suppressed_total 17883
telemt_desync_frames_bucket_total{bucket="1_2"} 6547
telemt_desync_frames_bucket_total{bucket="3_10"} 10411
telemt_desync_frames_bucket_total{bucket="gt_10"} 10171
telemt_pool_swap_total 139
telemt_pool_force_close_total 4147
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 43169
telemt_me_writer_removed_unexpected_total 1184
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40452
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39022
telemt_me_writer_teardown_success_total{mode="normal"} 44337
telemt_me_writer_teardown_noop_total 43181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.943319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1109
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 5780942
telemt_user_connections_current{user="hello"} 4171
telemt_user_octets_from_client{user="hello"} 149129106143 (138.89 GB)
telemt_user_octets_to_client{user="hello"} 2562157363411 (2.33 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1764
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 1235.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461257
telemt_connections_bad_total 45625
telemt_connections_current 6109
telemt_connections_me_current 6109
telemt_handshake_timeouts_total 5256
telemt_upstream_connect_attempt_total 478
telemt_upstream_connect_success_total 448
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 93
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 923432
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372233
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 15
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
telemt_me_writers_active_current 89
telemt_desync_total 640
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 250
telemt_me_writer_removed_unexpected_total 46
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 248
telemt_me_writer_teardown_success_total{mode="normal"} 296
telemt_me_writer_teardown_noop_total 250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 546
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.070252
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 546
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 372216
telemt_user_connections_current{user="hello"} 6109
telemt_user_octets_from_client{user="hello"} 2179089436 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 13700962508 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 2199
telemt_user_unique_ips_recent_window{user="hello"} 1166
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 130962.1 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7396347
telemt_connections_bad_total 666734
telemt_connections_current 3547
telemt_connections_me_current 3547
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 151720
telemt_upstream_connect_attempt_total 74960
telemt_upstream_connect_success_total 74142
telemt_upstream_connect_fail_total 700
telemt_upstream_connect_attempts_per_request{bucket="1"} 74842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 700
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70387
telemt_me_reconnect_success_total 2029
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1772
telemt_me_route_drop_no_conn_total 2899853
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5807768
telemt_me_endpoint_quarantine_total 885
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 990
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
telemt_me_writers_active_current 49
telemt_desync_total 29312
telemt_desync_full_logged_total 10195
telemt_desync_suppressed_total 19117
telemt_desync_frames_bucket_total{bucket="1_2"} 5851
telemt_desync_frames_bucket_total{bucket="3_10"} 11281
telemt_desync_frames_bucket_total{bucket="gt_10"} 12180
telemt_pool_swap_total 137
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 45401
telemt_me_writer_removed_unexpected_total 1803
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4599
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42631
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41469
telemt_me_writer_teardown_success_total{mode="normal"} 47230
telemt_me_writer_teardown_noop_total 45402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.373732
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1677
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 5805888
telemt_user_connections_current{user="hello"} 3547
telemt_user_octets_from_client{user="hello"} 147091958839 (136.99 GB)
telemt_user_octets_to_client{user="hello"} 2397126714995 (2.18 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1415
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 67798.1 (18h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5890254
telemt_connections_bad_total 231696
telemt_connections_current 4545
telemt_connections_me_current 4545
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2341708
telemt_upstream_connect_attempt_total 36301
telemt_upstream_connect_success_total 36046
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 36294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_reconnect_attempts_total 47419
telemt_me_reconnect_success_total 1227
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 1486943
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2956137
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 91
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16088
telemt_desync_full_logged_total 5461
telemt_desync_suppressed_total 10627
telemt_desync_frames_bucket_total{bucket="1_2"} 3164
telemt_desync_frames_bucket_total{bucket="3_10"} 6196
telemt_desync_frames_bucket_total{bucket="gt_10"} 6728
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24328
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2128
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23189
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22168
telemt_me_writer_teardown_success_total{mode="normal"} 25317
telemt_me_writer_teardown_noop_total 24334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.616728
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2957101
telemt_user_connections_current{user="hello"} 4545
telemt_user_octets_from_client{user="hello"} 75113476012 (69.95 GB)
telemt_user_octets_to_client{user="hello"} 1288007917366 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1916
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48768.9 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438143
telemt_connections_bad_total 2922
telemt_connections_current 917
telemt_connections_me_current 917
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8606
telemt_upstream_connect_attempt_total 25965
telemt_upstream_connect_success_total 25904
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 25959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1019
telemt_me_reconnect_success_total 393
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 140485
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395661
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 418
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
telemt_desync_total 1809
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1279
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 53
telemt_pool_force_close_total 1194
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 20883
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19795
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19689
telemt_me_writer_teardown_success_total{mode="normal"} 21272
telemt_me_writer_teardown_noop_total 20883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42155
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.868033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42155
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 342
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 397800
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 7873347533 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 201534500587 (187.69 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 130966.4 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9111676
telemt_connections_bad_total 1056178
telemt_connections_current 4672
telemt_connections_me_current 4672
telemt_handshake_timeouts_total 251180
telemt_upstream_connect_attempt_total 50839
telemt_upstream_connect_success_total 50645
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 50795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 1903
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1006
telemt_me_idle_close_by_peer_total 1006
telemt_me_route_drop_no_conn_total 2554781
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6746859
telemt_me_endpoint_quarantine_total 930
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 997
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
telemt_me_writers_active_current 44
telemt_desync_total 27150
telemt_desync_full_logged_total 8899
telemt_desync_suppressed_total 18251
telemt_desync_frames_bucket_total{bucket="1_2"} 6725
telemt_desync_frames_bucket_total{bucket="3_10"} 9892
telemt_desync_frames_bucket_total{bucket="gt_10"} 10533
telemt_pool_swap_total 145
telemt_pool_force_close_total 3902
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 474
telemt_me_draining_writers_reap_progress_total 45878
telemt_me_writer_removed_unexpected_total 967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3666
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43209
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41976
telemt_me_writer_teardown_success_total{mode="normal"} 46875
telemt_me_writer_teardown_noop_total 45880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.624935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 474
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 907
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6719758
telemt_user_connections_current{user="hello"} 4672
telemt_user_octets_from_client{user="hello"} 130850665636 (121.86 GB)
telemt_user_octets_to_client{user="hello"} 3159572677452 (2.87 TB)
telemt_user_unique_ips_current{user="hello"} 1727
telemt_user_unique_ips_recent_window{user="hello"} 643
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 130963.1 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7907093
telemt_connections_bad_total 882292
telemt_connections_current 4350
telemt_connections_me_current 4350
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 209382
telemt_upstream_connect_attempt_total 66876
telemt_upstream_connect_success_total 66357
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 66809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27220
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 631
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_reconnect_attempts_total 6399
telemt_me_reconnect_success_total 1467
telemt_me_reader_eof_total 1316
telemt_me_idle_close_by_peer_total 1316
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2697295
telemt_me_route_drop_channel_closed_total 233
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6018860
telemt_me_endpoint_quarantine_total 1023
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 994
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
telemt_desync_total 26009
telemt_desync_full_logged_total 8655
telemt_desync_suppressed_total 17354
telemt_desync_frames_bucket_total{bucket="1_2"} 6402
telemt_desync_frames_bucket_total{bucket="3_10"} 9554
telemt_desync_frames_bucket_total{bucket="gt_10"} 10053
telemt_pool_swap_total 142
telemt_pool_force_close_total 3848
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 468
telemt_me_draining_writers_reap_progress_total 44506
telemt_me_writer_removed_unexpected_total 1332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4270
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41630
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40658
telemt_me_writer_teardown_success_total{mode="normal"} 45900
telemt_me_writer_teardown_noop_total 44510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90410
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.242621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90410
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 468
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6019533
telemt_user_connections_current{user="hello"} 4350
telemt_user_octets_from_client{user="hello"} 110664820545 (103.06 GB)
telemt_user_octets_to_client{user="hello"} 2595419160000 (2.36 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1733
telemt_user_unique_ips_recent_window{user="hello"} 578
```