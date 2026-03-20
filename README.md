# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

## 4vps.su
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

# Server Metrics 2026-03-20 06:14:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 46612.5 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 922044
telemt_connections_bad_total 57839
telemt_connections_current 1452
telemt_connections_me_current 1452
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24001
telemt_upstream_connect_attempt_total 9056
telemt_upstream_connect_success_total 8952
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 9056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5574
telemt_me_reconnect_success_total 5530
telemt_me_reader_eof_total 5855
telemt_me_idle_close_by_peer_total 5854
telemt_me_route_drop_no_conn_total 258526
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 745695
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3961
telemt_desync_full_logged_total 1425
telemt_desync_suppressed_total 2536
telemt_desync_frames_bucket_total{bucket="1_2"} 770
telemt_desync_frames_bucket_total{bucket="3_10"} 1545
telemt_desync_frames_bucket_total{bucket="gt_10"} 1646
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 5589
telemt_me_writer_restored_same_endpoint_total 5517
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 747254
telemt_user_connections_current{user="hello"} 1452
telemt_user_octets_from_client{user="hello"} 33676821424 (31.36 GB)
telemt_user_octets_to_client{user="hello"} 259116057229 (241.32 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 63068.0 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4053673
telemt_connections_bad_total 368915
telemt_connections_current 4870
telemt_connections_me_current 4870
telemt_handshake_timeouts_total 96175
telemt_upstream_connect_attempt_total 11811
telemt_upstream_connect_success_total 11590
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 11811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11488
telemt_me_reconnect_success_total 7235
telemt_me_reader_eof_total 7738
telemt_me_idle_close_by_peer_total 7737
telemt_me_route_drop_no_conn_total 1819393
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3314445
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13353
telemt_desync_full_logged_total 4448
telemt_desync_suppressed_total 8905
telemt_desync_frames_bucket_total{bucket="1_2"} 2595
telemt_desync_frames_bucket_total{bucket="3_10"} 5195
telemt_desync_frames_bucket_total{bucket="gt_10"} 5563
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 7459
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7180
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 3314072
telemt_user_connections_current{user="hello"} 4870
telemt_user_octets_from_client{user="hello"} 49289558258 (45.90 GB)
telemt_user_octets_to_client{user="hello"} 1251997863694 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1637
telemt_user_unique_ips_recent_window{user="hello"} 645
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 63045.9 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3619382
telemt_connections_bad_total 507328
telemt_connections_current 3766
telemt_connections_me_current 3766
telemt_handshake_timeouts_total 55418
telemt_upstream_connect_attempt_total 10134
telemt_upstream_connect_success_total 10064
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 10134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7886
telemt_me_reconnect_success_total 6941
telemt_me_reader_eof_total 7318
telemt_me_idle_close_by_peer_total 7317
telemt_me_route_drop_no_conn_total 2124814
telemt_me_route_drop_channel_closed_total 206
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2551051
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9339
telemt_desync_full_logged_total 2922
telemt_desync_suppressed_total 6417
telemt_desync_frames_bucket_total{bucket="1_2"} 2339
telemt_desync_frames_bucket_total{bucket="3_10"} 3559
telemt_desync_frames_bucket_total{bucket="gt_10"} 3441
telemt_pool_swap_total 63
telemt_me_writer_close_signal_drop_total 82
telemt_me_writer_removed_unexpected_total 7020
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6940
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2546094
telemt_user_connections_current{user="hello"} 3766
telemt_user_octets_from_client{user="hello"} 38365475464 (35.73 GB)
telemt_user_octets_to_client{user="hello"} 1041298847792 (969.79 GB)
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 63033.8 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3580258
telemt_connections_bad_total 256810
telemt_connections_current 3930
telemt_connections_me_current 3930
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 53175
telemt_upstream_connect_attempt_total 67527
telemt_upstream_connect_success_total 62805
telemt_upstream_connect_fail_total 4722
telemt_upstream_connect_attempts_per_request{bucket="1"} 67527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4722
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10261
telemt_me_reconnect_success_total 7285
telemt_me_reader_eof_total 7600
telemt_me_idle_close_by_peer_total 7599
telemt_me_route_drop_no_conn_total 2988250
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2932725
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10697
telemt_desync_full_logged_total 3290
telemt_desync_suppressed_total 7407
telemt_desync_frames_bucket_total{bucket="1_2"} 2511
telemt_desync_frames_bucket_total{bucket="3_10"} 4044
telemt_desync_frames_bucket_total{bucket="gt_10"} 4142
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 675
telemt_me_writer_removed_unexpected_total 8003
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7281
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2983358
telemt_user_connections_current{user="hello"} 3930
telemt_user_octets_from_client{user="hello"} 42857354708 (39.91 GB)
telemt_user_octets_to_client{user="hello"} 808707008107 (753.17 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 526
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 616.8 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92471
telemt_connections_bad_total 12012
telemt_connections_current 4288
telemt_connections_me_current 4288
telemt_handshake_timeouts_total 1579
telemt_upstream_connect_attempt_total 143
telemt_upstream_connect_success_total 142
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 70614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72281
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 72136
telemt_user_connections_current{user="hello"} 4288
telemt_user_octets_from_client{user="hello"} 716310400 (683.13 MB)
telemt_user_octets_to_client{user="hello"} 15710169788 (14.63 GB)
telemt_user_unique_ips_current{user="hello"} 1337
telemt_user_unique_ips_recent_window{user="hello"} 536
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 551.9 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8706
telemt_connections_bad_total 60
telemt_connections_current 476
telemt_connections_me_current 476
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_route_drop_no_conn_total 1761
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7858
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 7841
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 48888548 (46.62 MB)
telemt_user_octets_to_client{user="hello"} 1966363440 (1.83 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 62998.4 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2645049
telemt_connections_bad_total 166042
telemt_connections_current 3729
telemt_connections_me_current 3729
telemt_handshake_timeouts_total 47088
telemt_upstream_connect_attempt_total 11171
telemt_upstream_connect_success_total 11103
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 11171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 8042
telemt_me_reconnect_success_total 7991
telemt_me_reader_eof_total 8447
telemt_me_idle_close_by_peer_total 8447
telemt_me_route_drop_no_conn_total 911669
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2214206
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11054
telemt_desync_full_logged_total 3630
telemt_desync_suppressed_total 7424
telemt_desync_frames_bucket_total{bucket="1_2"} 2156
telemt_desync_frames_bucket_total{bucket="3_10"} 3910
telemt_desync_frames_bucket_total{bucket="gt_10"} 4988
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8102
telemt_me_writer_restored_same_endpoint_total 7974
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2213018
telemt_user_connections_current{user="hello"} 3729
telemt_user_octets_from_client{user="hello"} 48554978108 (45.22 GB)
telemt_user_octets_to_client{user="hello"} 1167770039952 (1.06 TB)
telemt_user_unique_ips_current{user="hello"} 1221
telemt_user_unique_ips_recent_window{user="hello"} 450
```