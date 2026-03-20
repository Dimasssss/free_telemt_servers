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

# Server Metrics 2026-03-20 03:36:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 37137.3 (10h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684991
telemt_connections_bad_total 48405
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15046
telemt_upstream_connect_attempt_total 7561
telemt_upstream_connect_success_total 7468
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 7561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4526
telemt_me_reconnect_success_total 4486
telemt_me_reader_eof_total 4746
telemt_me_idle_close_by_peer_total 4745
telemt_me_route_drop_no_conn_total 193667
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542380
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2560
telemt_desync_full_logged_total 937
telemt_desync_suppressed_total 1623
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 930
telemt_desync_frames_bucket_total{bucket="gt_10"} 1109
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4525
telemt_me_writer_restored_same_endpoint_total 4473
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 543702
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 31208495244 (29.07 GB)
telemt_user_octets_to_client{user="hello"} 184901466193 (172.20 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 53593.1 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3246609
telemt_connections_bad_total 197773
telemt_connections_current 2111
telemt_connections_me_current 2111
telemt_handshake_timeouts_total 70080
telemt_upstream_connect_attempt_total 10417
telemt_upstream_connect_success_total 10233
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 10417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10586
telemt_me_reconnect_success_total 6337
telemt_me_reader_eof_total 6779
telemt_me_idle_close_by_peer_total 6779
telemt_me_route_drop_no_conn_total 1551715
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2736050
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11622
telemt_desync_full_logged_total 3840
telemt_desync_suppressed_total 7782
telemt_desync_frames_bucket_total{bucket="1_2"} 2232
telemt_desync_frames_bucket_total{bucket="3_10"} 4533
telemt_desync_frames_bucket_total{bucket="gt_10"} 4857
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6543
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6282
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 2735772
telemt_user_connections_current{user="hello"} 2111
telemt_user_octets_from_client{user="hello"} 41554517250 (38.70 GB)
telemt_user_octets_to_client{user="hello"} 1021949303090 (951.76 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 53571.0 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3098279
telemt_connections_bad_total 482448
telemt_connections_current 1725
telemt_connections_me_current 1725
telemt_handshake_timeouts_total 49455
telemt_upstream_connect_attempt_total 8765
telemt_upstream_connect_success_total 8700
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6970
telemt_me_reconnect_success_total 6033
telemt_me_reader_eof_total 6345
telemt_me_idle_close_by_peer_total 6344
telemt_me_route_drop_no_conn_total 1970823
telemt_me_route_drop_channel_closed_total 175
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2150845
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8001
telemt_desync_full_logged_total 2453
telemt_desync_suppressed_total 5548
telemt_desync_frames_bucket_total{bucket="1_2"} 1963
telemt_desync_frames_bucket_total{bucket="3_10"} 3039
telemt_desync_frames_bucket_total{bucket="gt_10"} 2999
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6094
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6032
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 2145871
telemt_user_connections_current{user="hello"} 1725
telemt_user_octets_from_client{user="hello"} 32702387344 (30.46 GB)
telemt_user_octets_to_client{user="hello"} 838831537568 (781.22 GB)
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 53558.9 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2782090
telemt_connections_bad_total 213896
telemt_connections_current 1620
telemt_connections_me_current 1620
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33208
telemt_upstream_connect_attempt_total 58719
telemt_upstream_connect_success_total 54303
telemt_upstream_connect_fail_total 4416
telemt_upstream_connect_attempts_per_request{bucket="1"} 58719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4416
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9312
telemt_me_reconnect_success_total 6403
telemt_me_reader_eof_total 6669
telemt_me_idle_close_by_peer_total 6668
telemt_me_route_drop_no_conn_total 1925586
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2250763
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8693
telemt_desync_full_logged_total 2778
telemt_desync_suppressed_total 5915
telemt_desync_frames_bucket_total{bucket="1_2"} 2133
telemt_desync_frames_bucket_total{bucket="3_10"} 3173
telemt_desync_frames_bucket_total{bucket="gt_10"} 3387
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7073
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6399
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 2294407
telemt_user_connections_current{user="hello"} 1620
telemt_user_octets_from_client{user="hello"} 36774238060 (34.25 GB)
telemt_user_octets_to_client{user="hello"} 665391194937 (619.69 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 107282.0 (29h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6483949
telemt_connections_bad_total 1117260
telemt_connections_current 1786
telemt_connections_me_current 1786
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 116219
telemt_upstream_connect_attempt_total 128743
telemt_upstream_connect_success_total 95451
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79451
telemt_me_reconnect_success_total 13777
telemt_me_reader_eof_total 14829
telemt_me_idle_close_by_peer_total 14815
telemt_me_route_drop_no_conn_total 2841563
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4574769
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
telemt_desync_total 19948
telemt_desync_full_logged_total 6338
telemt_desync_suppressed_total 13610
telemt_desync_frames_bucket_total{bucket="1_2"} 3526
telemt_desync_frames_bucket_total{bucket="3_10"} 8246
telemt_desync_frames_bucket_total{bucket="gt_10"} 8176
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 14093
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13752
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 4649839
telemt_user_connections_current{user="hello"} 1786
telemt_user_octets_from_client{user="hello"} 73930182568 (68.85 GB)
telemt_user_octets_to_client{user="hello"} 1809509313112 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 53521.9 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1081079
telemt_connections_bad_total 94422
telemt_connections_current 656
telemt_connections_me_current 656
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13518
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
telemt_me_route_drop_no_conn_total 473010
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
telemt_desync_total 1421
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 599
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
telemt_user_connections_total{user="hello"} 918666
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 7932458047 (7.39 GB)
telemt_user_octets_to_client{user="hello"} 146601719770 (136.53 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 53523.4 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2151134
telemt_connections_bad_total 127118
telemt_connections_current 1717
telemt_connections_me_current 1717
telemt_handshake_timeouts_total 40505
telemt_upstream_connect_attempt_total 9683
telemt_upstream_connect_success_total 9618
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6987
telemt_me_reconnect_success_total 6941
telemt_me_reader_eof_total 7330
telemt_me_idle_close_by_peer_total 7330
telemt_me_route_drop_no_conn_total 775133
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1831704
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9486
telemt_desync_full_logged_total 3061
telemt_desync_suppressed_total 6425
telemt_desync_frames_bucket_total{bucket="1_2"} 1834
telemt_desync_frames_bucket_total{bucket="3_10"} 3318
telemt_desync_frames_bucket_total{bucket="gt_10"} 4334
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7037
telemt_me_writer_restored_same_endpoint_total 6924
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1830803
telemt_user_connections_current{user="hello"} 1717
telemt_user_octets_from_client{user="hello"} 30927905124 (28.80 GB)
telemt_user_octets_to_client{user="hello"} 940611973092 (876.01 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 179
```