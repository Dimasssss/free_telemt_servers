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

# Server Metrics 2026-03-19 21:39:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 15711.3 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384709
telemt_connections_bad_total 19057
telemt_connections_current 753
telemt_connections_me_current 753
telemt_handshake_timeouts_total 5641
telemt_upstream_connect_attempt_total 2531
telemt_upstream_connect_success_total 2508
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1710
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1793
telemt_me_idle_close_by_peer_total 1793
telemt_me_route_drop_no_conn_total 117115
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305668
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1660
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 507
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1737
telemt_me_writer_restored_same_endpoint_total 1684
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 305938
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 11050125836 (10.29 GB)
telemt_user_octets_to_client{user="hello"} 115174308016 (107.26 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 32165.8 (8h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2699165
telemt_connections_bad_total 114305
telemt_connections_current 2009
telemt_connections_me_current 2009
telemt_handshake_timeouts_total 52882
telemt_upstream_connect_attempt_total 6581
telemt_upstream_connect_success_total 6478
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 6581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7862
telemt_me_reconnect_success_total 3633
telemt_me_reader_eof_total 3899
telemt_me_idle_close_by_peer_total 3899
telemt_me_route_drop_no_conn_total 1417947
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2302675
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10210
telemt_desync_full_logged_total 3318
telemt_desync_suppressed_total 6892
telemt_desync_frames_bucket_total{bucket="1_2"} 1901
telemt_desync_frames_bucket_total{bucket="3_10"} 3984
telemt_desync_frames_bucket_total{bucket="gt_10"} 4325
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3800
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3578
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2302553
telemt_user_connections_current{user="hello"} 2009
telemt_user_octets_from_client{user="hello"} 36388776314 (33.89 GB)
telemt_user_octets_to_client{user="hello"} 818015951270 (761.84 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 826
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 32143.8 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2633900
telemt_connections_bad_total 456182
telemt_connections_current 1513
telemt_connections_me_current 1513
telemt_handshake_timeouts_total 32791
telemt_upstream_connect_attempt_total 4981
telemt_upstream_connect_success_total 4942
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4248
telemt_me_reconnect_success_total 3322
telemt_me_reader_eof_total 3449
telemt_me_idle_close_by_peer_total 3448
telemt_me_route_drop_no_conn_total 1845374
telemt_me_route_drop_channel_closed_total 165
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1843057
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7034
telemt_desync_full_logged_total 2120
telemt_desync_suppressed_total 4914
telemt_desync_frames_bucket_total{bucket="1_2"} 1774
telemt_desync_frames_bucket_total{bucket="3_10"} 2672
telemt_desync_frames_bucket_total{bucket="gt_10"} 2588
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3342
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3321
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1838995
telemt_user_connections_current{user="hello"} 1513
telemt_user_octets_from_client{user="hello"} 27545422068 (25.65 GB)
telemt_user_octets_to_client{user="hello"} 667902240720 (622.03 GB)
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 32131.7 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304694
telemt_connections_bad_total 94706
telemt_connections_current 1513
telemt_connections_me_current 1513
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29077
telemt_upstream_connect_attempt_total 35193
telemt_upstream_connect_success_total 33479
telemt_upstream_connect_fail_total 1714
telemt_upstream_connect_attempts_per_request{bucket="1"} 35193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1714
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6386
telemt_me_reconnect_success_total 3780
telemt_me_reader_eof_total 3918
telemt_me_idle_close_by_peer_total 3917
telemt_me_route_drop_no_conn_total 1807201
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1963885
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7893
telemt_desync_full_logged_total 2464
telemt_desync_suppressed_total 5429
telemt_desync_frames_bucket_total{bucket="1_2"} 1946
telemt_desync_frames_bucket_total{bucket="3_10"} 2869
telemt_desync_frames_bucket_total{bucket="gt_10"} 3078
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 347
telemt_me_writer_removed_unexpected_total 4290
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3776
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1990827
telemt_user_connections_current{user="hello"} 1513
telemt_user_octets_from_client{user="hello"} 32888599472 (30.63 GB)
telemt_user_octets_to_client{user="hello"} 500897274783 (466.50 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 570
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 85854.9 (23h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5977561
telemt_connections_bad_total 1030980
telemt_connections_current 1773
telemt_connections_me_current 1773
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108406
telemt_upstream_connect_attempt_total 66593
telemt_upstream_connect_success_total 64090
telemt_upstream_connect_fail_total 2503
telemt_upstream_connect_attempts_per_request{bucket="1"} 66593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76034
telemt_me_reconnect_success_total 10616
telemt_me_reader_eof_total 11208
telemt_me_idle_close_by_peer_total 11205
telemt_me_route_drop_no_conn_total 2728449
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4238038
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
telemt_desync_total 18612
telemt_desync_full_logged_total 5785
telemt_desync_suppressed_total 12827
telemt_desync_frames_bucket_total{bucket="1_2"} 3215
telemt_desync_frames_bucket_total{bucket="3_10"} 7690
telemt_desync_frames_bucket_total{bucket="gt_10"} 7707
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 10879
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10592
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 4286087
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 66584201795 (62.01 GB)
telemt_user_octets_to_client{user="hello"} 1654087124880 (1.50 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 698
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 32095.1 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 616607
telemt_connections_bad_total 48903
telemt_connections_current 469
telemt_connections_me_current 469
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11814
telemt_upstream_connect_attempt_total 9045
telemt_upstream_connect_success_total 8834
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 562
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4301
telemt_me_reconnect_success_total 4223
telemt_me_reader_eof_total 4394
telemt_me_idle_close_by_peer_total 4392
telemt_me_route_drop_no_conn_total 411597
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499724
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
telemt_desync_total 1348
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4261
telemt_me_writer_restored_same_endpoint_total 4214
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 509710
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 6748785904 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 115264142298 (107.35 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 32096.4 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1822531
telemt_connections_bad_total 106058
telemt_connections_current 1681
telemt_connections_me_current 1681
telemt_handshake_timeouts_total 32865
telemt_upstream_connect_attempt_total 5321
telemt_upstream_connect_success_total 5281
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3686
telemt_me_reconnect_success_total 3652
telemt_me_reader_eof_total 3842
telemt_me_idle_close_by_peer_total 3842
telemt_me_route_drop_no_conn_total 683996
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1582823
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8459
telemt_desync_full_logged_total 2657
telemt_desync_suppressed_total 5802
telemt_desync_frames_bucket_total{bucket="1_2"} 1562
telemt_desync_frames_bucket_total{bucket="3_10"} 2954
telemt_desync_frames_bucket_total{bucket="gt_10"} 3943
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3721
telemt_me_writer_restored_same_endpoint_total 3635
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1581973
telemt_user_connections_current{user="hello"} 1681
telemt_user_octets_from_client{user="hello"} 26959094320 (25.11 GB)
telemt_user_octets_to_client{user="hello"} 780104742592 (726.53 GB)
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 159
```