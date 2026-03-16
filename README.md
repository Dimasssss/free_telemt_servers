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

# Server Metrics 2026-03-16 11:08:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 132831.3 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 715082
telemt_connections_bad_total 53840
telemt_handshake_timeouts_total 23004
telemt_upstream_connect_attempt_total 30833
telemt_upstream_connect_success_total 30685
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 30833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 38314
telemt_me_reconnect_success_total 24089
telemt_me_reader_eof_total 26008
telemt_me_idle_close_by_peer_total 26008
telemt_me_route_drop_no_conn_total 596818
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 659044
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3027
telemt_desync_full_logged_total 1164
telemt_desync_suppressed_total 1863
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 1188
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24792
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24054
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 595578
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 11504480552 (10.71 GB)
telemt_user_octets_to_client{user="hello"} 352453905296 (328.25 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 132838.4 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285691
telemt_connections_bad_total 3801
telemt_handshake_timeouts_total 16965
telemt_upstream_connect_attempt_total 35639
telemt_upstream_connect_success_total 35532
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 822
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1679
telemt_me_reconnect_attempts_total 38666
telemt_me_reconnect_success_total 28315
telemt_me_reader_eof_total 30358
telemt_me_idle_close_by_peer_total 30357
telemt_me_route_drop_no_conn_total 139059
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253819
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29041
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28299
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 253534
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 5314733873 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 131218215176 (122.21 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 132830.9 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283749
telemt_connections_bad_total 5848
telemt_handshake_timeouts_total 7394
telemt_upstream_connect_attempt_total 37005
telemt_upstream_connect_success_total 36997
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37752
telemt_me_reconnect_success_total 30322
telemt_me_reader_eof_total 32554
telemt_me_idle_close_by_peer_total 32553
telemt_me_route_drop_no_conn_total 97639
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231139
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30858
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30314
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 230782
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 18762809181 (17.47 GB)
telemt_user_octets_to_client{user="hello"} 125968995116 (117.32 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 132830.9 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421014
telemt_connections_bad_total 1424
telemt_handshake_timeouts_total 3920
telemt_upstream_connect_attempt_total 30678
telemt_upstream_connect_success_total 30634
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 30678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 29016
telemt_me_reconnect_success_total 24014
telemt_me_reader_eof_total 25732
telemt_me_idle_close_by_peer_total 25731
telemt_me_route_drop_no_conn_total 145165
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390570
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 967
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24494
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24003
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 390438
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 6266000006 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 151604630864 (141.19 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 107902.1 (29h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263110
telemt_connections_bad_total 44983
telemt_handshake_timeouts_total 4369
telemt_upstream_connect_attempt_total 30812
telemt_upstream_connect_success_total 30645
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 30811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 119632
telemt_me_reconnect_success_total 25118
telemt_me_reader_eof_total 26650
telemt_me_idle_close_by_peer_total 26650
telemt_me_route_drop_no_conn_total 80668
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205619
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 683
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 25332
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 25014
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 205240
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2626197613 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 90897769403 (84.66 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 132830.4 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929109
telemt_connections_bad_total 73490
telemt_handshake_timeouts_total 10957
telemt_upstream_connect_attempt_total 28018
telemt_upstream_connect_success_total 27871
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 28018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 23861
telemt_me_reconnect_success_total 21248
telemt_me_reader_eof_total 22688
telemt_me_idle_close_by_peer_total 22687
telemt_me_route_drop_no_conn_total 690158
telemt_me_route_drop_channel_closed_total 126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912555
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 513
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 173
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 21583
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21221
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 771172
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 16165543328 (15.06 GB)
telemt_user_octets_to_client{user="hello"} 449073393404 (418.23 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 115
```