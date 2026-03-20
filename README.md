# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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

# Server Metrics 2026-03-20 07:17:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 50395.0 (13h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049406
telemt_connections_bad_total 62691
telemt_connections_current 1735
telemt_connections_me_current 1735
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27166
telemt_upstream_connect_attempt_total 9736
telemt_upstream_connect_success_total 9628
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 9736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6076
telemt_me_reconnect_success_total 6031
telemt_me_reader_eof_total 6379
telemt_me_idle_close_by_peer_total 6378
telemt_me_route_drop_no_conn_total 303406
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860024
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4392
telemt_desync_full_logged_total 1584
telemt_desync_suppressed_total 2808
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1700
telemt_desync_frames_bucket_total{bucket="gt_10"} 1810
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 6097
telemt_me_writer_restored_same_endpoint_total 6018
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 859458
telemt_user_connections_current{user="hello"} 1735
telemt_user_octets_from_client{user="hello"} 35041949188 (32.64 GB)
telemt_user_octets_to_client{user="hello"} 296233474937 (275.89 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 66851.0 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4885730
telemt_connections_bad_total 437545
telemt_connections_current 5734
telemt_connections_me_current 5734
telemt_handshake_timeouts_total 102435
telemt_upstream_connect_attempt_total 12463
telemt_upstream_connect_success_total 12206
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 12463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5251
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 11918
telemt_me_reconnect_success_total 7647
telemt_me_reader_eof_total 8185
telemt_me_idle_close_by_peer_total 8184
telemt_me_route_drop_no_conn_total 2869802
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4031733
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14969
telemt_desync_full_logged_total 4939
telemt_desync_suppressed_total 10030
telemt_desync_frames_bucket_total{bucket="1_2"} 2960
telemt_desync_frames_bucket_total{bucket="3_10"} 5848
telemt_desync_frames_bucket_total{bucket="gt_10"} 6161
telemt_pool_swap_total 59
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 105
telemt_me_writer_removed_unexpected_total 7887
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7592
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 4033575
telemt_user_connections_current{user="hello"} 5734
telemt_user_octets_from_client{user="hello"} 54046455198 (50.33 GB)
telemt_user_octets_to_client{user="hello"} 1344360116606 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1717
telemt_user_unique_ips_recent_window{user="hello"} 1148
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 191.9 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697
telemt_connections_bad_total 159
telemt_connections_current 145
telemt_connections_me_current 145
telemt_upstream_connect_attempt_total 157
telemt_upstream_connect_success_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_me_reconnect_attempts_total 43
telemt_me_reconnect_success_total 40
telemt_me_route_drop_no_conn_total 114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_close_signal_drop_total 19
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_restored_same_endpoint_total 40
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 446
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1852884 (1.77 MB)
telemt_user_octets_to_client{user="hello"} 75544739 (72.05 MB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 66828.6 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4184365
telemt_connections_bad_total 539563
telemt_connections_current 4034
telemt_connections_me_current 4034
telemt_handshake_timeouts_total 64478
telemt_upstream_connect_attempt_total 12314
telemt_upstream_connect_success_total 12208
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3085
telemt_me_reconnect_attempts_total 8369
telemt_me_reconnect_success_total 7406
telemt_me_reader_eof_total 7749
telemt_me_idle_close_by_peer_total 7744
telemt_me_route_drop_no_conn_total 2764579
telemt_me_route_drop_channel_closed_total 261
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3005792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10582
telemt_desync_full_logged_total 3313
telemt_desync_suppressed_total 7269
telemt_desync_frames_bucket_total{bucket="1_2"} 2542
telemt_desync_frames_bucket_total{bucket="3_10"} 4046
telemt_desync_frames_bucket_total{bucket="gt_10"} 3994
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 316
telemt_me_writer_removed_unexpected_total 7502
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7405
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 3012163
telemt_user_connections_current{user="hello"} 4034
telemt_user_octets_from_client{user="hello"} 41960319602 (39.08 GB)
telemt_user_octets_to_client{user="hello"} 1125131303544 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1362
telemt_user_unique_ips_recent_window{user="hello"} 556
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 66816.3 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4634925
telemt_connections_bad_total 286833
telemt_connections_current 4999
telemt_connections_me_current 4999
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 65218
telemt_upstream_connect_attempt_total 68108
telemt_upstream_connect_success_total 63368
telemt_upstream_connect_fail_total 4740
telemt_upstream_connect_attempts_per_request{bucket="1"} 68108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4740
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 10620
telemt_me_reconnect_success_total 7633
telemt_me_reader_eof_total 7975
telemt_me_idle_close_by_peer_total 7974
telemt_me_route_drop_no_conn_total 5429858
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3896651
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12861
telemt_desync_full_logged_total 3733
telemt_desync_suppressed_total 9128
telemt_desync_frames_bucket_total{bucket="1_2"} 2899
telemt_desync_frames_bucket_total{bucket="3_10"} 5072
telemt_desync_frames_bucket_total{bucket="gt_10"} 4890
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 678
telemt_me_writer_removed_unexpected_total 8362
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7629
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 3947961
telemt_user_connections_current{user="hello"} 4999
telemt_user_octets_from_client{user="hello"} 46490636568 (43.30 GB)
telemt_user_octets_to_client{user="hello"} 851702457251 (793.21 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1408
telemt_user_unique_ips_recent_window{user="hello"} 859
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 4399.2 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723368
telemt_connections_bad_total 67166
telemt_connections_current 5040
telemt_connections_me_current 5040
telemt_handshake_timeouts_total 12901
telemt_upstream_connect_attempt_total 663
telemt_upstream_connect_success_total 660
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 413
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 928369
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599752
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1641
telemt_desync_full_logged_total 498
telemt_desync_suppressed_total 1143
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 650
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_restored_same_endpoint_total 383
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 599711
telemt_user_connections_current{user="hello"} 5040
telemt_user_octets_from_client{user="hello"} 7946506244 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 110695213948 (103.09 GB)
telemt_user_unique_ips_current{user="hello"} 1602
telemt_user_unique_ips_recent_window{user="hello"} 680
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4335.3 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70516
telemt_connections_bad_total 12965
telemt_connections_current 710
telemt_connections_me_current 710
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 809
telemt_upstream_connect_success_total 802
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 559
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 557
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 37962
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67898
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 53689
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 572398156 (545.88 MB)
telemt_user_octets_to_client{user="hello"} 21498577352 (20.02 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 66781.0 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2968146
telemt_connections_bad_total 185831
telemt_connections_current 4827
telemt_connections_me_current 4827
telemt_handshake_timeouts_total 54454
telemt_upstream_connect_attempt_total 11780
telemt_upstream_connect_success_total 11706
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 11780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8428
telemt_me_reconnect_success_total 8372
telemt_me_reader_eof_total 8852
telemt_me_idle_close_by_peer_total 8852
telemt_me_route_drop_no_conn_total 1014229
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2496039
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12387
telemt_desync_full_logged_total 4041
telemt_desync_suppressed_total 8346
telemt_desync_frames_bucket_total{bucket="1_2"} 2494
telemt_desync_frames_bucket_total{bucket="3_10"} 4366
telemt_desync_frames_bucket_total{bucket="gt_10"} 5527
telemt_pool_swap_total 69
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8490
telemt_me_writer_restored_same_endpoint_total 8355
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 2494130
telemt_user_connections_current{user="hello"} 4827
telemt_user_octets_from_client{user="hello"} 53758526600 (50.07 GB)
telemt_user_octets_to_client{user="hello"} 1304015136376 (1.19 TB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 615
```