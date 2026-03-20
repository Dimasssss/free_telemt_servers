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

# Server Metrics 2026-03-20 01:59:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 31325.3 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587541
telemt_connections_bad_total 37655
telemt_connections_current 767
telemt_connections_me_current 767
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9278
telemt_upstream_connect_attempt_total 6561
telemt_upstream_connect_success_total 6476
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 6561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3835
telemt_me_reconnect_success_total 3800
telemt_me_reader_eof_total 4009
telemt_me_idle_close_by_peer_total 4008
telemt_me_route_drop_no_conn_total 167636
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468949
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2182
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 756
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3828
telemt_me_writer_restored_same_endpoint_total 3787
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 470377
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 29946487288 (27.89 GB)
telemt_user_octets_to_client{user="hello"} 165205519849 (153.86 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 47779.8 (13h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3023988
telemt_connections_bad_total 127579
telemt_connections_current 1388
telemt_connections_me_current 1388
telemt_handshake_timeouts_total 66680
telemt_upstream_connect_attempt_total 9475
telemt_upstream_connect_success_total 9318
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 9475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9941
telemt_me_reconnect_success_total 5697
telemt_me_reader_eof_total 6094
telemt_me_idle_close_by_peer_total 6094
telemt_me_route_drop_no_conn_total 1508990
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2592115
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11229
telemt_desync_full_logged_total 3699
telemt_desync_suppressed_total 7530
telemt_desync_frames_bucket_total{bucket="1_2"} 2146
telemt_desync_frames_bucket_total{bucket="3_10"} 4393
telemt_desync_frames_bucket_total{bucket="gt_10"} 4690
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5894
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5642
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 2591894
telemt_user_connections_current{user="hello"} 1388
telemt_user_octets_from_client{user="hello"} 39531783102 (36.82 GB)
telemt_user_octets_to_client{user="hello"} 954695815390 (889.13 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 47757.8 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2972211
telemt_connections_bad_total 476706
telemt_connections_current 1049
telemt_connections_me_current 1049
telemt_handshake_timeouts_total 44145
telemt_upstream_connect_attempt_total 7718
telemt_upstream_connect_success_total 7660
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6207
telemt_me_reconnect_success_total 5274
telemt_me_reader_eof_total 5534
telemt_me_idle_close_by_peer_total 5533
telemt_me_route_drop_no_conn_total 1925908
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2048964
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7691
telemt_desync_full_logged_total 2334
telemt_desync_suppressed_total 5357
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 2923
telemt_desync_frames_bucket_total{bucket="gt_10"} 2868
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5326
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5273
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2044586
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 30179913048 (28.11 GB)
telemt_user_octets_to_client{user="hello"} 786824430860 (732.79 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 47745.8 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2594954
telemt_connections_bad_total 141189
telemt_connections_current 1041
telemt_connections_me_current 1041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31376
telemt_upstream_connect_attempt_total 55611
telemt_upstream_connect_success_total 51328
telemt_upstream_connect_fail_total 4283
telemt_upstream_connect_attempts_per_request{bucket="1"} 55611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 529
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4283
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8553
telemt_me_reconnect_success_total 5710
telemt_me_reader_eof_total 5938
telemt_me_idle_close_by_peer_total 5937
telemt_me_route_drop_no_conn_total 1868050
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2152701
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8364
telemt_desync_full_logged_total 2644
telemt_desync_suppressed_total 5720
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3041
telemt_desync_frames_bucket_total{bucket="gt_10"} 3261
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 477
telemt_me_writer_removed_unexpected_total 6338
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5706
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 2194772
telemt_user_connections_current{user="hello"} 1041
telemt_user_octets_from_client{user="hello"} 35739160037 (33.28 GB)
telemt_user_octets_to_client{user="hello"} 618071087505 (575.62 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 430
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 101469.1 (28h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6294262
telemt_connections_bad_total 1045603
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113870
telemt_upstream_connect_attempt_total 127681
telemt_upstream_connect_success_total 94395
telemt_upstream_connect_fail_total 33286
telemt_upstream_connect_attempts_per_request{bucket="1"} 127681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33286
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78696
telemt_me_reconnect_success_total 13026
telemt_me_reader_eof_total 14028
telemt_me_idle_close_by_peer_total 14014
telemt_me_route_drop_no_conn_total 2802725
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4464278
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19575
telemt_desync_full_logged_total 6205
telemt_desync_suppressed_total 13370
telemt_desync_frames_bucket_total{bucket="1_2"} 3449
telemt_desync_frames_bucket_total{bucket="3_10"} 8057
telemt_desync_frames_bucket_total{bucket="gt_10"} 8069
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 13335
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13001
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4539491
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 72634605136 (67.65 GB)
telemt_user_octets_to_client{user="hello"} 1744657512864 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 47709.1 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726902
telemt_connections_bad_total 77443
telemt_connections_current 379
telemt_connections_me_current 379
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13074
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 471283
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 585947
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 7405657523 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 146470041202 (136.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 47710.3 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2039901
telemt_connections_bad_total 120309
telemt_connections_current 1241
telemt_connections_me_current 1241
telemt_handshake_timeouts_total 37799
telemt_upstream_connect_attempt_total 8508
telemt_upstream_connect_success_total 8448
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6119
telemt_me_reconnect_success_total 6076
telemt_me_reader_eof_total 6413
telemt_me_idle_close_by_peer_total 6413
telemt_me_route_drop_no_conn_total 746741
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1751389
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9274
telemt_desync_full_logged_total 2985
telemt_desync_suppressed_total 6289
telemt_desync_frames_bucket_total{bucket="1_2"} 1754
telemt_desync_frames_bucket_total{bucket="3_10"} 3251
telemt_desync_frames_bucket_total{bucket="gt_10"} 4269
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6167
telemt_me_writer_restored_same_endpoint_total 6059
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 1750496
telemt_user_connections_current{user="hello"} 1241
telemt_user_octets_from_client{user="hello"} 29959671272 (27.90 GB)
telemt_user_octets_to_client{user="hello"} 887545252796 (826.59 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 105
```