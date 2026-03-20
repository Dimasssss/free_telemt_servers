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

# Server Metrics 2026-03-20 05:43:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 44777.4 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866545
telemt_connections_bad_total 56340
telemt_connections_current 1294
telemt_connections_me_current 1294
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21382
telemt_upstream_connect_attempt_total 8739
telemt_upstream_connect_success_total 8639
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 8739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5351
telemt_me_reconnect_success_total 5307
telemt_me_reader_eof_total 5624
telemt_me_idle_close_by_peer_total 5623
telemt_me_route_drop_no_conn_total 241652
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697101
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3715
telemt_desync_full_logged_total 1337
telemt_desync_suppressed_total 2378
telemt_desync_frames_bucket_total{bucket="1_2"} 705
telemt_desync_frames_bucket_total{bucket="3_10"} 1459
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 46
telemt_me_writer_removed_unexpected_total 5362
telemt_me_writer_restored_same_endpoint_total 5294
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 698633
telemt_user_connections_current{user="hello"} 1294
telemt_user_octets_from_client{user="hello"} 33232822876 (30.95 GB)
telemt_user_octets_to_client{user="hello"} 242395760565 (225.75 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 61233.0 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3841110
telemt_connections_bad_total 344149
telemt_connections_current 4296
telemt_connections_me_current 4296
telemt_handshake_timeouts_total 91323
telemt_upstream_connect_attempt_total 11496
telemt_upstream_connect_success_total 11285
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 11496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11286
telemt_me_reconnect_success_total 7035
telemt_me_reader_eof_total 7528
telemt_me_idle_close_by_peer_total 7527
telemt_me_route_drop_no_conn_total 1710883
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3146741
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12827
telemt_desync_full_logged_total 4290
telemt_desync_suppressed_total 8537
telemt_desync_frames_bucket_total{bucket="1_2"} 2439
telemt_desync_frames_bucket_total{bucket="3_10"} 4979
telemt_desync_frames_bucket_total{bucket="gt_10"} 5409
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 58
telemt_me_writer_removed_unexpected_total 7254
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6980
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 3146452
telemt_user_connections_current{user="hello"} 4296
telemt_user_octets_from_client{user="hello"} 47395128070 (44.14 GB)
telemt_user_octets_to_client{user="hello"} 1196633606302 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1475
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 61211.1 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3470628
telemt_connections_bad_total 499665
telemt_connections_current 3284
telemt_connections_me_current 3284
telemt_handshake_timeouts_total 53788
telemt_upstream_connect_attempt_total 9875
telemt_upstream_connect_success_total 9807
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 9875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7732
telemt_me_reconnect_success_total 6788
telemt_me_reader_eof_total 7155
telemt_me_idle_close_by_peer_total 7154
telemt_me_route_drop_no_conn_total 2070802
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2443022
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8985
telemt_desync_full_logged_total 2783
telemt_desync_suppressed_total 6202
telemt_desync_frames_bucket_total{bucket="1_2"} 2238
telemt_desync_frames_bucket_total{bucket="3_10"} 3421
telemt_desync_frames_bucket_total{bucket="gt_10"} 3326
telemt_pool_swap_total 61
telemt_me_writer_close_signal_drop_total 77
telemt_me_writer_removed_unexpected_total 6863
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6787
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 2438064
telemt_user_connections_current{user="hello"} 3284
telemt_user_octets_from_client{user="hello"} 36855003072 (34.32 GB)
telemt_user_octets_to_client{user="hello"} 997542455856 (929.03 GB)
telemt_user_unique_ips_current{user="hello"} 1137
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 61198.8 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3225867
telemt_connections_bad_total 241207
telemt_connections_current 3562
telemt_connections_me_current 3562
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 47407
telemt_upstream_connect_attempt_total 67255
telemt_upstream_connect_success_total 62549
telemt_upstream_connect_fail_total 4706
telemt_upstream_connect_attempts_per_request{bucket="1"} 67255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 711
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4706
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10091
telemt_me_reconnect_success_total 7123
telemt_me_reader_eof_total 7422
telemt_me_idle_close_by_peer_total 7421
telemt_me_route_drop_no_conn_total 2252745
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2621164
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9730
telemt_desync_full_logged_total 3093
telemt_desync_suppressed_total 6637
telemt_desync_frames_bucket_total{bucket="1_2"} 2311
telemt_desync_frames_bucket_total{bucket="3_10"} 3605
telemt_desync_frames_bucket_total{bucket="gt_10"} 3814
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 674
telemt_me_writer_removed_unexpected_total 7834
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7119
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 2671567
telemt_user_connections_current{user="hello"} 3562
telemt_user_octets_from_client{user="hello"} 40579277532 (37.79 GB)
telemt_user_octets_to_client{user="hello"} 784309956859 (730.45 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1101
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 114922.1 (31h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6926233
telemt_connections_bad_total 1207498
telemt_connections_current 3762
telemt_connections_me_current 3762
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 121882
telemt_upstream_connect_attempt_total 129844
telemt_upstream_connect_success_total 96541
telemt_upstream_connect_fail_total 33303
telemt_upstream_connect_attempts_per_request{bucket="1"} 129844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33303
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80197
telemt_me_reconnect_success_total 14517
telemt_me_reader_eof_total 15620
telemt_me_idle_close_by_peer_total 15606
telemt_me_route_drop_no_conn_total 2983337
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4895889
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
telemt_desync_total 21196
telemt_desync_full_logged_total 6744
telemt_desync_suppressed_total 14452
telemt_desync_frames_bucket_total{bucket="1_2"} 3769
telemt_desync_frames_bucket_total{bucket="3_10"} 8772
telemt_desync_frames_bucket_total{bucket="gt_10"} 8655
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 14850
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14492
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 333
telemt_user_connections_total{user="hello"} 4970627
telemt_user_connections_current{user="hello"} 3762
telemt_user_octets_from_client{user="hello"} 78884907728 (73.47 GB)
telemt_user_octets_to_client{user="hello"} 1973108068988 (1.79 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1247
telemt_user_unique_ips_recent_window{user="hello"} 478
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 61162.2 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1690404
telemt_connections_bad_total 107425
telemt_connections_current 1081
telemt_connections_me_current 1081
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14867
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 60
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473701
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
telemt_desync_total 1616
telemt_desync_full_logged_total 594
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 724
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
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
telemt_user_connections_total{user="hello"} 1505162
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 9344398111 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 146636350382 (136.57 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 61163.4 (16h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2517543
telemt_connections_bad_total 155993
telemt_connections_current 3271
telemt_connections_me_current 3271
telemt_handshake_timeouts_total 45310
telemt_upstream_connect_attempt_total 10903
telemt_upstream_connect_success_total 10836
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7861
telemt_me_reconnect_success_total 7811
telemt_me_reader_eof_total 8255
telemt_me_idle_close_by_peer_total 8255
telemt_me_route_drop_no_conn_total 874909
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2109596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10636
telemt_desync_full_logged_total 3477
telemt_desync_suppressed_total 7159
telemt_desync_frames_bucket_total{bucket="1_2"} 2072
telemt_desync_frames_bucket_total{bucket="3_10"} 3740
telemt_desync_frames_bucket_total{bucket="gt_10"} 4824
telemt_pool_swap_total 62
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 7919
telemt_me_writer_restored_same_endpoint_total 7794
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 2108287
telemt_user_connections_current{user="hello"} 3271
telemt_user_octets_from_client{user="hello"} 45810993744 (42.66 GB)
telemt_user_octets_to_client{user="hello"} 1115893364312 (1.01 TB)
telemt_user_unique_ips_current{user="hello"} 1085
telemt_user_unique_ips_recent_window{user="hello"} 381
```