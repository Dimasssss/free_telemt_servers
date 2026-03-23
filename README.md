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

# Server Metrics 2026-03-23 01:21:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 101684.7 (28h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3529549
telemt_connections_bad_total 313417
telemt_connections_current 935
telemt_connections_me_current 935
telemt_handshake_timeouts_total 109638
telemt_upstream_connect_attempt_total 37769
telemt_upstream_connect_success_total 37768
telemt_upstream_connect_attempts_per_request{bucket="1"} 37768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1399
telemt_me_reconnect_success_total 605
telemt_me_reader_eof_total 621
telemt_me_idle_close_by_peer_total 621
telemt_me_route_drop_no_conn_total 2986301
telemt_me_route_drop_channel_closed_total 1234
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2913103
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 712
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 792
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12518
telemt_desync_full_logged_total 3931
telemt_desync_suppressed_total 8587
telemt_desync_frames_bucket_total{bucket="1_2"} 3371
telemt_desync_frames_bucket_total{bucket="3_10"} 4562
telemt_desync_frames_bucket_total{bucket="gt_10"} 4585
telemt_pool_swap_total 112
telemt_pool_force_close_total 3457
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34577
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2481
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32343
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31120
telemt_me_writer_teardown_success_total{mode="normal"} 34824
telemt_me_writer_teardown_noop_total 34588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 378.031961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 541
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2902183
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 41486146056 (38.64 GB)
telemt_user_octets_to_client{user="hello"} 795143390736 (740.53 GB)
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 115050.6 (31h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4003723
telemt_connections_bad_total 369002
telemt_connections_current 378
telemt_connections_me_current 378
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100790
telemt_upstream_connect_attempt_total 71816
telemt_upstream_connect_success_total 70966
telemt_upstream_connect_fail_total 757
telemt_upstream_connect_attempts_per_request{bucket="1"} 71723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 757
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10100
telemt_me_reconnect_success_total 3615
telemt_me_reader_eof_total 3613
telemt_me_idle_close_by_peer_total 3613
telemt_me_route_drop_no_conn_total 3641270
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3180794
telemt_me_endpoint_quarantine_total 912
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 897
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 12964
telemt_desync_full_logged_total 7271
telemt_desync_suppressed_total 5693
telemt_desync_frames_bucket_total{bucket="1_2"} 2941
telemt_desync_frames_bucket_total{bucket="3_10"} 5082
telemt_desync_frames_bucket_total{bucket="gt_10"} 4941
telemt_pool_swap_total 107
telemt_pool_force_close_total 3071
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 47376
telemt_me_writer_removed_unexpected_total 3543
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6217
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44735
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2613
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44305
telemt_me_writer_teardown_success_total{mode="normal"} 50952
telemt_me_writer_teardown_noop_total 47377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98329
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.618865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98329
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 3229
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 3194095
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 43079184235 (40.12 GB)
telemt_user_octets_to_client{user="hello"} 791985076452 (737.59 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 189910.4 (52h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16345301
telemt_connections_bad_total 1653401
telemt_connections_current 1075
telemt_connections_me_current 1075
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397520
telemt_upstream_connect_attempt_total 85127
telemt_upstream_connect_success_total 85022
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 85039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3007
telemt_me_reconnect_success_total 1581
telemt_me_reader_eof_total 1528
telemt_me_idle_close_by_peer_total 1526
telemt_me_route_drop_no_conn_total 14046958
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12979663
telemt_me_endpoint_quarantine_total 1257
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1428
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53853
telemt_desync_full_logged_total 17100
telemt_desync_suppressed_total 36753
telemt_desync_frames_bucket_total{bucket="1_2"} 12003
telemt_desync_frames_bucket_total{bucket="3_10"} 21018
telemt_desync_frames_bucket_total{bucket="gt_10"} 20832
telemt_pool_swap_total 205
telemt_pool_force_close_total 6722
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1063
telemt_me_draining_writers_reap_progress_total 64517
telemt_me_writer_removed_unexpected_total 1471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5497
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57795
telemt_me_writer_teardown_success_total{mode="normal"} 65264
telemt_me_writer_teardown_noop_total 64570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.780125
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1063
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1368
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12979692
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 191194467765 (178.06 GB)
telemt_user_octets_to_client{user="hello"} 3490185288259 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 189911.8 (52h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11885668
telemt_connections_bad_total 1236581
telemt_connections_current 523
telemt_connections_me_current 523
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344611
telemt_upstream_connect_attempt_total 99487
telemt_upstream_connect_success_total 98161
telemt_upstream_connect_fail_total 873
telemt_upstream_connect_attempts_per_request{bucket="1"} 99034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 873
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4436
telemt_me_reconnect_success_total 1886
telemt_me_reader_eof_total 1752
telemt_me_idle_close_by_peer_total 1752
telemt_me_route_drop_no_conn_total 4556691
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8822893
telemt_me_endpoint_quarantine_total 1266
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1446
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
telemt_me_writers_active_current 47
telemt_desync_total 38813
telemt_desync_full_logged_total 13070
telemt_desync_suppressed_total 25743
telemt_desync_frames_bucket_total{bucket="1_2"} 9613
telemt_desync_frames_bucket_total{bucket="3_10"} 14905
telemt_desync_frames_bucket_total{bucket="gt_10"} 14295
telemt_pool_swap_total 202
telemt_pool_force_close_total 6079
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 62731
telemt_me_writer_removed_unexpected_total 1782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56652
telemt_me_writer_teardown_success_total{mode="normal"} 64369
telemt_me_writer_teardown_noop_total 62756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127125
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.431497
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127125
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1613
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8760652
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 217828498852 (202.87 GB)
telemt_user_octets_to_client{user="hello"} 3964377632523 (3.61 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 189876.1 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11062322
telemt_connections_bad_total 975829
telemt_connections_current 498
telemt_connections_me_current 498
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345602
telemt_upstream_connect_attempt_total 83756
telemt_upstream_connect_success_total 82197
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 82402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5753
telemt_me_reconnect_success_total 2375
telemt_me_reader_eof_total 2120
telemt_me_idle_close_by_peer_total 2119
telemt_me_route_drop_no_conn_total 5338034
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8361353
telemt_me_endpoint_quarantine_total 1332
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1405
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38184
telemt_desync_full_logged_total 12642
telemt_desync_suppressed_total 25542
telemt_desync_frames_bucket_total{bucket="1_2"} 9643
telemt_desync_frames_bucket_total{bucket="3_10"} 14608
telemt_desync_frames_bucket_total{bucket="gt_10"} 13933
telemt_pool_swap_total 198
telemt_pool_force_close_total 5979
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 740
telemt_me_draining_writers_reap_progress_total 63095
telemt_me_writer_removed_unexpected_total 2270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58961
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57116
telemt_me_writer_teardown_success_total{mode="normal"} 65297
telemt_me_writer_teardown_noop_total 63166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.788943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 740
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2065
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8353312
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 192781546123 (179.54 GB)
telemt_user_octets_to_client{user="hello"} 3472049546509 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60155.9 (16h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11255475
telemt_connections_bad_total 669192
telemt_connections_current 939
telemt_connections_me_current 939
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 273609
telemt_upstream_connect_attempt_total 58236
telemt_upstream_connect_success_total 55175
telemt_upstream_connect_fail_total 2028
telemt_upstream_connect_attempts_per_request{bucket="1"} 57203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2028
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7762
telemt_me_reconnect_success_total 1251
telemt_me_reader_eof_total 782
telemt_me_idle_close_by_peer_total 781
telemt_me_route_drop_no_conn_total 25291511
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9338775
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 482
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 16344
telemt_desync_full_logged_total 4460
telemt_desync_suppressed_total 11884
telemt_desync_frames_bucket_total{bucket="1_2"} 3094
telemt_desync_frames_bucket_total{bucket="3_10"} 6658
telemt_desync_frames_bucket_total{bucket="gt_10"} 6592
telemt_pool_swap_total 62
telemt_pool_force_close_total 2020
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 18869
telemt_me_writer_removed_unexpected_total 1139
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2552
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1713
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16849
telemt_me_writer_teardown_success_total{mode="normal"} 19951
telemt_me_writer_teardown_noop_total 18888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.889287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 339
telemt_me_writer_restored_same_endpoint_total 802
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 326
telemt_user_connections_total{user="hello"} 9364655
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 87305172570 (81.31 GB)
telemt_user_octets_to_client{user="hello"} 610512303774 (568.58 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 189882.4 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10999447
telemt_connections_bad_total 947860
telemt_connections_current 699
telemt_connections_me_current 699
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242305
telemt_upstream_connect_attempt_total 112648
telemt_upstream_connect_success_total 111487
telemt_upstream_connect_fail_total 987
telemt_upstream_connect_attempts_per_request{bucket="1"} 112474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 987
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72949
telemt_me_reconnect_success_total 3088
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2774
telemt_me_route_drop_no_conn_total 5264023
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8680885
telemt_me_endpoint_quarantine_total 1278
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1433
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 45
telemt_desync_total 46265
telemt_desync_full_logged_total 15850
telemt_desync_suppressed_total 30415
telemt_desync_frames_bucket_total{bucket="1_2"} 9403
telemt_desync_frames_bucket_total{bucket="3_10"} 17710
telemt_desync_frames_bucket_total{bucket="gt_10"} 19152
telemt_pool_swap_total 194
telemt_pool_force_close_total 5692
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67248
telemt_me_writer_removed_unexpected_total 2804
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4943
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61556
telemt_me_writer_teardown_success_total{mode="normal"} 70088
telemt_me_writer_teardown_noop_total 67249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.269132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 4300
telemt_me_writer_restored_same_endpoint_total 2604
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 8683861
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 194656100533 (181.29 GB)
telemt_user_octets_to_client{user="hello"} 3319984625224 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 126718.7 (35h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11706512
telemt_connections_bad_total 482492
telemt_connections_current 483
telemt_connections_me_current 483
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4762065
telemt_upstream_connect_attempt_total 61007
telemt_upstream_connect_success_total 60563
telemt_upstream_connect_fail_total 433
telemt_upstream_connect_attempts_per_request{bucket="1"} 60996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 433
telemt_me_reconnect_attempts_total 48988
telemt_me_reconnect_success_total 1823
telemt_me_reader_eof_total 1495
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 4093985
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5625181
telemt_me_endpoint_quarantine_total 855
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 972
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31634
telemt_desync_full_logged_total 10793
telemt_desync_suppressed_total 20841
telemt_desync_frames_bucket_total{bucket="1_2"} 6297
telemt_desync_frames_bucket_total{bucket="3_10"} 12476
telemt_desync_frames_bucket_total{bucket="gt_10"} 12861
telemt_pool_swap_total 134
telemt_pool_force_close_total 3907
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 46535
telemt_me_writer_removed_unexpected_total 1546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3466
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42628
telemt_me_writer_teardown_success_total{mode="normal"} 48124
telemt_me_writer_teardown_noop_total 46542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.692954
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 2740
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 28
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5617336
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 119128739228 (110.95 GB)
telemt_user_octets_to_client{user="hello"} 2181315608722 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 107689.7 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1527587
telemt_connections_bad_total 36772
telemt_connections_current 414
telemt_connections_me_current 414
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 31031
telemt_upstream_connect_attempt_total 50777
telemt_upstream_connect_success_total 50619
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 791
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2251
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 902
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 518376
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1357676
telemt_me_endpoint_quarantine_total 893
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 891
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
telemt_me_writers_active_current 44
telemt_desync_total 9055
telemt_desync_full_logged_total 2635
telemt_desync_suppressed_total 6420
telemt_desync_frames_bucket_total{bucket="1_2"} 2559
telemt_desync_frames_bucket_total{bucket="3_10"} 3452
telemt_desync_frames_bucket_total{bucket="gt_10"} 3044
telemt_pool_swap_total 116
telemt_pool_force_close_total 2961
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 42981
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2873
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40020
telemt_me_writer_teardown_success_total{mode="normal"} 43890
telemt_me_writer_teardown_noop_total 42985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.314478
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 1353490
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 26038789657 (24.25 GB)
telemt_user_octets_to_client{user="hello"} 576052991411 (536.49 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 189887.0 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13328872
telemt_connections_bad_total 1600896
telemt_connections_current 596
telemt_connections_me_current 596
telemt_handshake_timeouts_total 389039
telemt_upstream_connect_attempt_total 74831
telemt_upstream_connect_success_total 74480
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 74695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2981
telemt_me_reconnect_success_total 1496
telemt_me_reader_eof_total 1480
telemt_me_idle_close_by_peer_total 1480
telemt_me_route_drop_no_conn_total 4483758
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10052350
telemt_me_endpoint_quarantine_total 1356
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1435
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 48
telemt_desync_total 42097
telemt_desync_full_logged_total 13749
telemt_desync_suppressed_total 28348
telemt_desync_frames_bucket_total{bucket="1_2"} 10187
telemt_desync_frames_bucket_total{bucket="3_10"} 15474
telemt_desync_frames_bucket_total{bucket="gt_10"} 16436
telemt_pool_swap_total 210
telemt_pool_force_close_total 5596
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 67635
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5327
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5422
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62039
telemt_me_writer_teardown_success_total{mode="normal"} 69105
telemt_me_writer_teardown_noop_total 67637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.790093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1313
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10019057
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 194822685528 (181.44 GB)
telemt_user_octets_to_client{user="hello"} 4440921139196 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 189883.5 (52h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11648293
telemt_connections_bad_total 1362719
telemt_connections_current 524
telemt_connections_me_current 524
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311715
telemt_upstream_connect_attempt_total 102309
telemt_upstream_connect_success_total 101421
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 102101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43113
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10477
telemt_me_reconnect_success_total 2585
telemt_me_reader_eof_total 2398
telemt_me_idle_close_by_peer_total 2397
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5651018
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8963056
telemt_me_endpoint_quarantine_total 1531
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1437
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 41819
telemt_desync_full_logged_total 13461
telemt_desync_suppressed_total 28358
telemt_desync_frames_bucket_total{bucket="1_2"} 10804
telemt_desync_frames_bucket_total{bucket="3_10"} 15380
telemt_desync_frames_bucket_total{bucket="gt_10"} 15635
telemt_pool_swap_total 200
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67669
telemt_me_writer_removed_unexpected_total 2439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6677
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63516
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62293
telemt_me_writer_teardown_success_total{mode="normal"} 70193
telemt_me_writer_teardown_noop_total 67674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.469812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2081
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8967643
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 157378719328 (146.57 GB)
telemt_user_octets_to_client{user="hello"} 3491014087278 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 47
```