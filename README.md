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

# Server Metrics 2026-03-17 06:29:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 42257.2 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249306
telemt_connections_bad_total 3358
telemt_handshake_timeouts_total 8114
telemt_upstream_connect_attempt_total 8782
telemt_upstream_connect_success_total 8736
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6675
telemt_me_reconnect_success_total 6650
telemt_me_reader_eof_total 7078
telemt_me_idle_close_by_peer_total 7078
telemt_me_route_drop_no_conn_total 77586
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225526
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1161
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 852
telemt_desync_frames_bucket_total{bucket="gt_10"} 448
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6718
telemt_me_writer_restored_same_endpoint_total 6629
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 225313
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 3048702780 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 98401412220 (91.64 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 42508.6 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141998
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10765
telemt_upstream_connect_attempt_total 11641
telemt_upstream_connect_success_total 11494
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 11641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 10549
telemt_me_reconnect_success_total 9373
telemt_me_reader_eof_total 9916
telemt_me_idle_close_by_peer_total 9916
telemt_me_route_drop_no_conn_total 53001
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123684
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9494
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9357
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 123693
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 1518623896 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 52601749972 (48.99 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 42284.7 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84602
telemt_connections_bad_total 1110
telemt_handshake_timeouts_total 2754
telemt_upstream_connect_attempt_total 11336
telemt_upstream_connect_success_total 11277
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 11336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9221
telemt_me_reconnect_success_total 9171
telemt_me_reader_eof_total 9814
telemt_me_idle_close_by_peer_total 9814
telemt_me_route_drop_no_conn_total 28943
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9281
telemt_me_writer_restored_same_endpoint_total 9160
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 72994
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 6131379812 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 23627413964 (22.00 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 42343.8 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150228
telemt_connections_bad_total 3791
telemt_handshake_timeouts_total 6148
telemt_upstream_connect_attempt_total 9524
telemt_upstream_connect_success_total 9443
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_reconnect_attempts_total 7348
telemt_me_reconnect_success_total 7292
telemt_me_reader_eof_total 7763
telemt_me_idle_close_by_peer_total 7763
telemt_me_route_drop_no_conn_total 49978
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135816
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7398
telemt_me_writer_restored_same_endpoint_total 7285
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 135833
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 1476773698 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 65994458757 (61.46 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 42315.8 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114209
telemt_connections_bad_total 33548
telemt_handshake_timeouts_total 2368
telemt_upstream_connect_attempt_total 12789
telemt_upstream_connect_success_total 12620
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 12789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 12682
telemt_me_reconnect_success_total 10416
telemt_me_reader_eof_total 10978
telemt_me_idle_close_by_peer_total 10978
telemt_me_route_drop_no_conn_total 28882
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75143
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10623
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 10408
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 75240
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 791721991 (755.04 MB)
telemt_user_octets_to_client{user="hello"} 34050955962 (31.71 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 42476.8 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273042
telemt_connections_bad_total 38007
telemt_handshake_timeouts_total 2179
telemt_upstream_connect_attempt_total 8669
telemt_upstream_connect_success_total 8623
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6524
telemt_me_reconnect_success_total 6495
telemt_me_reader_eof_total 6965
telemt_me_idle_close_by_peer_total 6965
telemt_me_route_drop_no_conn_total 222330
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300897
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 257
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 6592
telemt_me_writer_restored_same_endpoint_total 6485
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 222835
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 3317738992 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 154212046588 (143.62 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 30483.3 (8h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1031
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 15151
telemt_upstream_connect_success_total 15151
telemt_upstream_connect_attempts_per_request{bucket="1"} 15151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 13651
telemt_me_reconnect_success_total 13576
telemt_me_reader_eof_total 14851
telemt_me_idle_close_by_peer_total 14851
telemt_me_route_drop_no_conn_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 13701
telemt_me_writer_restored_same_endpoint_total 13576
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 824
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 198495776 (189.30 MB)
telemt_user_octets_to_client{user="hello"} 11918460008 (11.10 GB)
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```