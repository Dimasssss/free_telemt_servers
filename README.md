# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
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

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 12:58:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 19511.3 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103609
telemt_connections_bad_total 541
telemt_handshake_timeouts_total 3601
telemt_upstream_connect_attempt_total 4776
telemt_upstream_connect_success_total 4754
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 208
telemt_me_reconnect_attempts_total 3765
telemt_me_reconnect_success_total 3739
telemt_me_reader_eof_total 3904
telemt_me_idle_close_by_peer_total 3903
telemt_me_route_drop_no_conn_total 28839
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92573
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 162
telemt_desync_suppressed_total 276
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3766
telemt_me_writer_restored_same_endpoint_total 3723
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 92538
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1295177520 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 34281476324 (31.93 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 19404.4 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41927
telemt_connections_bad_total 335
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 5758
telemt_upstream_connect_success_total 5613
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 5758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 20445
telemt_me_reconnect_success_total 4622
telemt_me_reader_eof_total 5170
telemt_me_idle_close_by_peer_total 5170
telemt_me_route_drop_no_conn_total 18045
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39915
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 5134
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 4607
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 39915
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 467832656 (446.16 MB)
telemt_user_octets_to_client{user="hello"} 10778870876 (10.04 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 19367.9 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56669
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 567
telemt_upstream_connect_attempt_total 5303
telemt_upstream_connect_success_total 5303
telemt_upstream_connect_attempts_per_request{bucket="1"} 5303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4315
telemt_me_reconnect_success_total 4284
telemt_me_reader_eof_total 4518
telemt_me_idle_close_by_peer_total 4518
telemt_me_route_drop_no_conn_total 19769
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53361
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4306
telemt_me_writer_restored_same_endpoint_total 4264
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 53344
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 1754718488 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 32935023412 (30.67 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 19343.7 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72748
telemt_connections_bad_total 1083
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 5294
telemt_upstream_connect_success_total 5159
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 5294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 10692
telemt_me_reconnect_success_total 4147
telemt_me_reader_eof_total 4477
telemt_me_idle_close_by_peer_total 4477
telemt_me_route_drop_no_conn_total 24464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66752
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 131
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4401
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4139
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 66753
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1127200220 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 31498541392 (29.34 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 19313.1 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41079
telemt_connections_bad_total 3653
telemt_handshake_timeouts_total 648
telemt_upstream_connect_attempt_total 9538
telemt_upstream_connect_success_total 9304
telemt_upstream_connect_fail_total 234
telemt_upstream_connect_attempts_per_request{bucket="1"} 9538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 234
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 24545
telemt_me_reconnect_success_total 3609
telemt_me_reader_eof_total 4260
telemt_me_idle_close_by_peer_total 4260
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 11412
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31052
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 404
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4284
telemt_me_refill_failed_total 655
telemt_me_writer_restored_same_endpoint_total 3592
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 675
telemt_user_connections_total{user="hello"} 35738
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 252624970 (240.92 MB)
telemt_user_octets_to_client{user="hello"} 8676333287 (8.08 GB)
telemt_user_msgs_from_client{user="hello"} 54126
telemt_user_msgs_to_client{user="hello"} 176247
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19300.0 (5h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110216
telemt_connections_bad_total 763
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 3933
telemt_upstream_connect_success_total 3912
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 2940
telemt_me_reconnect_success_total 2913
telemt_me_reader_eof_total 3071
telemt_me_idle_close_by_peer_total 3071
telemt_me_route_drop_no_conn_total 45053
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 209
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2951
telemt_me_writer_restored_same_endpoint_total 2906
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 104870
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 2552177044 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 48449750416 (45.12 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 46
```