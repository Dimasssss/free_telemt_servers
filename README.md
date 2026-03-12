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

# Server Metrics 2026-03-12 14:56:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 26563.5 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141077
telemt_connections_bad_total 1509
telemt_handshake_timeouts_total 4559
telemt_upstream_connect_attempt_total 6461
telemt_upstream_connect_success_total 6436
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 5094
telemt_me_reconnect_success_total 5059
telemt_me_reader_eof_total 5316
telemt_me_idle_close_by_peer_total 5315
telemt_me_route_drop_no_conn_total 40357
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122896
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 571
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5105
telemt_me_writer_restored_same_endpoint_total 5043
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 122859
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 2063912648 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 45897505644 (42.75 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 26456.4 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58980
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 378
telemt_upstream_connect_attempt_total 8145
telemt_upstream_connect_success_total 7967
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 23535
telemt_me_reconnect_success_total 6612
telemt_me_reader_eof_total 7288
telemt_me_idle_close_by_peer_total 7288
telemt_me_route_drop_no_conn_total 26234
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56269
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 7184
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 6597
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 56261
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 631671796 (602.41 MB)
telemt_user_octets_to_client{user="hello"} 16086045820 (14.98 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 26419.9 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80702
telemt_connections_bad_total 1429
telemt_handshake_timeouts_total 1543
telemt_upstream_connect_attempt_total 7153
telemt_upstream_connect_success_total 7153
telemt_upstream_connect_attempts_per_request{bucket="1"} 7153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 5805
telemt_me_reconnect_success_total 5753
telemt_me_reader_eof_total 6084
telemt_me_idle_close_by_peer_total 6084
telemt_me_route_drop_no_conn_total 28550
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74355
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 5801
telemt_me_writer_restored_same_endpoint_total 5733
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 74327
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1984412200 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 40981340676 (38.17 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 26395.6 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104413
telemt_connections_bad_total 5201
telemt_handshake_timeouts_total 767
telemt_upstream_connect_attempt_total 6689
telemt_upstream_connect_success_total 6509
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 6689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 22279
telemt_me_reconnect_success_total 5139
telemt_me_reader_eof_total 5809
telemt_me_idle_close_by_peer_total 5809
telemt_me_route_drop_no_conn_total 37872
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92702
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 312
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5734
telemt_me_refill_failed_total 534
telemt_me_writer_restored_same_endpoint_total 5131
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 595
telemt_user_connections_total{user="hello"} 92585
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1768150408 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 38217021328 (35.59 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26365.1 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61308
telemt_connections_bad_total 5117
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 25628
telemt_upstream_connect_success_total 25299
telemt_upstream_connect_fail_total 329
telemt_upstream_connect_attempts_per_request{bucket="1"} 25628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4589
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 329
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 35583
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4677
telemt_me_idle_close_by_peer_total 4677
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12509
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4702
telemt_me_refill_failed_total 998
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1018
telemt_user_connections_total{user="hello"} 53689
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 448345402 (427.58 MB)
telemt_user_octets_to_client{user="hello"} 14765579304 (13.75 GB)
telemt_user_msgs_from_client{user="hello"} 302224
telemt_user_msgs_to_client{user="hello"} 1159610
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26352.6 (7h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162685
telemt_connections_bad_total 895
telemt_handshake_timeouts_total 1250
telemt_upstream_connect_attempt_total 5413
telemt_upstream_connect_success_total 5385
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 4059
telemt_me_reconnect_success_total 4028
telemt_me_reader_eof_total 4240
telemt_me_idle_close_by_peer_total 4240
telemt_me_route_drop_no_conn_total 63214
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155587
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 237
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4075
telemt_me_writer_restored_same_endpoint_total 4021
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 155553
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 3128097748 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 71341728552 (66.44 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 74
```