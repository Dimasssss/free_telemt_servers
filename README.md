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

# Server Metrics 2026-03-20 05:18:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 43249.3 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824200
telemt_connections_bad_total 54973
telemt_connections_current 1110
telemt_connections_me_current 1110
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18920
telemt_upstream_connect_attempt_total 8484
telemt_upstream_connect_success_total 8386
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 8484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5168
telemt_me_reconnect_success_total 5125
telemt_me_reader_eof_total 5428
telemt_me_idle_close_by_peer_total 5427
telemt_me_route_drop_no_conn_total 229761
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662068
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3540
telemt_desync_full_logged_total 1274
telemt_desync_suppressed_total 2266
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1470
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5176
telemt_me_writer_restored_same_endpoint_total 5112
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 663581
telemt_user_connections_current{user="hello"} 1110
telemt_user_octets_from_client{user="hello"} 32669442872 (30.43 GB)
telemt_user_octets_to_client{user="hello"} 225993071049 (210.47 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 59704.9 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3711707
telemt_connections_bad_total 331385
telemt_connections_current 3849
telemt_connections_me_current 3849
telemt_handshake_timeouts_total 86478
telemt_upstream_connect_attempt_total 11331
telemt_upstream_connect_success_total 11124
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 11331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11173
telemt_me_reconnect_success_total 6922
telemt_me_reader_eof_total 7406
telemt_me_idle_close_by_peer_total 7406
telemt_me_route_drop_no_conn_total 1665779
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038427
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12511
telemt_desync_full_logged_total 4189
telemt_desync_suppressed_total 8322
telemt_desync_frames_bucket_total{bucket="1_2"} 2386
telemt_desync_frames_bucket_total{bucket="3_10"} 4843
telemt_desync_frames_bucket_total{bucket="gt_10"} 5282
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 7138
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6867
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3038144
telemt_user_connections_current{user="hello"} 3849
telemt_user_octets_from_client{user="hello"} 45905131890 (42.75 GB)
telemt_user_octets_to_client{user="hello"} 1154725091122 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1376
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 59682.8 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3364976
telemt_connections_bad_total 493885
telemt_connections_current 2865
telemt_connections_me_current 2865
telemt_handshake_timeouts_total 52465
telemt_upstream_connect_attempt_total 9706
telemt_upstream_connect_success_total 9638
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 9706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7606
telemt_me_reconnect_success_total 6663
telemt_me_reader_eof_total 7021
telemt_me_idle_close_by_peer_total 7020
telemt_me_route_drop_no_conn_total 2043841
telemt_me_route_drop_channel_closed_total 183
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2363676
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8701
telemt_desync_full_logged_total 2687
telemt_desync_suppressed_total 6014
telemt_desync_frames_bucket_total{bucket="1_2"} 2166
telemt_desync_frames_bucket_total{bucket="3_10"} 3303
telemt_desync_frames_bucket_total{bucket="gt_10"} 3232
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 76
telemt_me_writer_removed_unexpected_total 6735
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6662
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 2358727
telemt_user_connections_current{user="hello"} 2865
telemt_user_octets_from_client{user="hello"} 35755315216 (33.30 GB)
telemt_user_octets_to_client{user="hello"} 958530856832 (892.70 GB)
telemt_user_unique_ips_current{user="hello"} 1010
telemt_user_unique_ips_recent_window{user="hello"} 365
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 59670.7 (16h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3060034
telemt_connections_bad_total 227612
telemt_connections_current 2879
telemt_connections_me_current 2879
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 42729
telemt_upstream_connect_attempt_total 63675
telemt_upstream_connect_success_total 59106
telemt_upstream_connect_fail_total 4569
telemt_upstream_connect_attempts_per_request{bucket="1"} 63675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4569
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9933
telemt_me_reconnect_success_total 6991
telemt_me_reader_eof_total 7305
telemt_me_idle_close_by_peer_total 7304
telemt_me_route_drop_no_conn_total 2086567
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2488322
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9497
telemt_desync_full_logged_total 3027
telemt_desync_suppressed_total 6470
telemt_desync_frames_bucket_total{bucket="1_2"} 2264
telemt_desync_frames_bucket_total{bucket="3_10"} 3511
telemt_desync_frames_bucket_total{bucket="gt_10"} 3722
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7680
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6987
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 2535504
telemt_user_connections_current{user="hello"} 2879
telemt_user_octets_from_client{user="hello"} 39553925353 (36.84 GB)
telemt_user_octets_to_client{user="hello"} 761390885879 (709.10 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 985
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 113394.0 (31h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6815866
telemt_connections_bad_total 1194108
telemt_connections_current 3307
telemt_connections_me_current 3307
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 120748
telemt_upstream_connect_attempt_total 129631
telemt_upstream_connect_success_total 96329
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80071
telemt_me_reconnect_success_total 14391
telemt_me_reader_eof_total 15483
telemt_me_idle_close_by_peer_total 15469
telemt_me_route_drop_no_conn_total 2925649
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4809623
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
telemt_desync_total 20913
telemt_desync_full_logged_total 6649
telemt_desync_suppressed_total 14264
telemt_desync_frames_bucket_total{bucket="1_2"} 3710
telemt_desync_frames_bucket_total{bucket="3_10"} 8651
telemt_desync_frames_bucket_total{bucket="gt_10"} 8552
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 14720
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14366
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 4884676
telemt_user_connections_current{user="hello"} 3307
telemt_user_octets_from_client{user="hello"} 77308786292 (72.00 GB)
telemt_user_octets_to_client{user="hello"} 1930748602604 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1097
telemt_user_unique_ips_recent_window{user="hello"} 380
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 59633.9 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539352
telemt_connections_bad_total 103196
telemt_connections_current 938
telemt_connections_me_current 938
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14340
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
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
telemt_me_route_drop_no_conn_total 473593
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
telemt_desync_total 1539
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
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
telemt_user_connections_total{user="hello"} 1361408
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 9060100099 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 146631015074 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 59635.4 (16h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2418625
telemt_connections_bad_total 153809
telemt_connections_current 2856
telemt_connections_me_current 2856
telemt_handshake_timeouts_total 44355
telemt_upstream_connect_attempt_total 10721
telemt_upstream_connect_success_total 10654
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7722
telemt_me_reconnect_success_total 7673
telemt_me_reader_eof_total 8111
telemt_me_idle_close_by_peer_total 8111
telemt_me_route_drop_no_conn_total 851105
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031151
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10357
telemt_desync_full_logged_total 3354
telemt_desync_suppressed_total 7003
telemt_desync_frames_bucket_total{bucket="1_2"} 2009
telemt_desync_frames_bucket_total{bucket="3_10"} 3652
telemt_desync_frames_bucket_total{bucket="gt_10"} 4696
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7779
telemt_me_writer_restored_same_endpoint_total 7656
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 2029845
telemt_user_connections_current{user="hello"} 2856
telemt_user_octets_from_client{user="hello"} 43358899704 (40.38 GB)
telemt_user_octets_to_client{user="hello"} 1072998932596 (999.31 GB)
telemt_user_unique_ips_current{user="hello"} 957
telemt_user_unique_ips_recent_window{user="hello"} 336
```