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

# Server Metrics 2026-03-20 03:21:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 36220.1 (10h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 668887
telemt_connections_bad_total 45629
telemt_connections_current 832
telemt_connections_me_current 832
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14886
telemt_upstream_connect_attempt_total 7413
telemt_upstream_connect_success_total 7321
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 7413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4422
telemt_me_reconnect_success_total 4382
telemt_me_reader_eof_total 4635
telemt_me_idle_close_by_peer_total 4634
telemt_me_route_drop_no_conn_total 187680
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529817
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2487
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1581
telemt_desync_frames_bucket_total{bucket="1_2"} 514
telemt_desync_frames_bucket_total{bucket="3_10"} 890
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4419
telemt_me_writer_restored_same_endpoint_total 4369
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 531250
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 31024336952 (28.89 GB)
telemt_user_octets_to_client{user="hello"} 181555074057 (169.09 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 52675.7 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3202573
telemt_connections_bad_total 182898
telemt_connections_current 2008
telemt_connections_me_current 2008
telemt_handshake_timeouts_total 69791
telemt_upstream_connect_attempt_total 10285
telemt_upstream_connect_success_total 10104
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 10285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10500
telemt_me_reconnect_success_total 6251
telemt_me_reader_eof_total 6689
telemt_me_idle_close_by_peer_total 6689
telemt_me_route_drop_no_conn_total 1543248
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2708110
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11561
telemt_desync_full_logged_total 3822
telemt_desync_suppressed_total 7739
telemt_desync_frames_bucket_total{bucket="1_2"} 2217
telemt_desync_frames_bucket_total{bucket="3_10"} 4513
telemt_desync_frames_bucket_total{bucket="gt_10"} 4831
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6457
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6196
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 2707841
telemt_user_connections_current{user="hello"} 2008
telemt_user_octets_from_client{user="hello"} 41129059322 (38.30 GB)
telemt_user_octets_to_client{user="hello"} 1007828432430 (938.61 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 52653.7 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3072716
telemt_connections_bad_total 481253
telemt_connections_current 1683
telemt_connections_me_current 1683
telemt_handshake_timeouts_total 49072
telemt_upstream_connect_attempt_total 8613
telemt_upstream_connect_success_total 8552
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6865
telemt_me_reconnect_success_total 5929
telemt_me_reader_eof_total 6233
telemt_me_idle_close_by_peer_total 6232
telemt_me_route_drop_no_conn_total 1964489
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2130495
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7964
telemt_desync_full_logged_total 2443
telemt_desync_suppressed_total 5521
telemt_desync_frames_bucket_total{bucket="1_2"} 1956
telemt_desync_frames_bucket_total{bucket="3_10"} 3019
telemt_desync_frames_bucket_total{bucket="gt_10"} 2989
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 72
telemt_me_writer_removed_unexpected_total 5987
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5928
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 2125520
telemt_user_connections_current{user="hello"} 1683
telemt_user_octets_from_client{user="hello"} 32496573880 (30.26 GB)
telemt_user_octets_to_client{user="hello"} 828131171256 (771.26 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 52641.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2755870
telemt_connections_bad_total 209967
telemt_connections_current 1498
telemt_connections_me_current 1498
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32749
telemt_upstream_connect_attempt_total 58579
telemt_upstream_connect_success_total 54166
telemt_upstream_connect_fail_total 4413
telemt_upstream_connect_attempts_per_request{bucket="1"} 58579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4413
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9218
telemt_me_reconnect_success_total 6309
telemt_me_reader_eof_total 6571
telemt_me_idle_close_by_peer_total 6570
telemt_me_route_drop_no_conn_total 1890872
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2230677
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8625
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 5875
telemt_desync_frames_bucket_total{bucket="1_2"} 2125
telemt_desync_frames_bucket_total{bucket="3_10"} 3144
telemt_desync_frames_bucket_total{bucket="gt_10"} 3356
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 6979
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6305
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 2274740
telemt_user_connections_current{user="hello"} 1498
telemt_user_octets_from_client{user="hello"} 36554154252 (34.04 GB)
telemt_user_octets_to_client{user="hello"} 653916718249 (609.01 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 106364.6 (29h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6418398
telemt_connections_bad_total 1076649
telemt_connections_current 1689
telemt_connections_me_current 1689
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115596
telemt_upstream_connect_attempt_total 128585
telemt_upstream_connect_success_total 95294
telemt_upstream_connect_fail_total 33291
telemt_upstream_connect_attempts_per_request{bucket="1"} 128585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33291
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79337
telemt_me_reconnect_success_total 13664
telemt_me_reader_eof_total 14711
telemt_me_idle_close_by_peer_total 14697
telemt_me_route_drop_no_conn_total 2832411
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4552277
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
telemt_desync_total 19878
telemt_desync_full_logged_total 6313
telemt_desync_suppressed_total 13565
telemt_desync_frames_bucket_total{bucket="1_2"} 3507
telemt_desync_frames_bucket_total{bucket="3_10"} 8217
telemt_desync_frames_bucket_total{bucket="gt_10"} 8154
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 13979
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13639
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 4627350
telemt_user_connections_current{user="hello"} 1689
telemt_user_octets_from_client{user="hello"} 73618926840 (68.56 GB)
telemt_user_octets_to_client{user="hello"} 1798509748304 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 691
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 52604.5 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1023387
telemt_connections_bad_total 92588
telemt_connections_current 787
telemt_connections_me_current 787
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13431
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
telemt_me_route_drop_no_conn_total 472746
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
telemt_user_connections_total{user="hello"} 863684
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 7851590951 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 146598230830 (136.53 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 52605.9 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2130089
telemt_connections_bad_total 124920
telemt_connections_current 1527
telemt_connections_me_current 1527
telemt_handshake_timeouts_total 39625
telemt_upstream_connect_attempt_total 9517
telemt_upstream_connect_success_total 9452
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6864
telemt_me_reconnect_success_total 6818
telemt_me_reader_eof_total 7201
telemt_me_idle_close_by_peer_total 7201
telemt_me_route_drop_no_conn_total 769657
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1814255
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9440
telemt_desync_full_logged_total 3046
telemt_desync_suppressed_total 6394
telemt_desync_frames_bucket_total{bucket="1_2"} 1812
telemt_desync_frames_bucket_total{bucket="3_10"} 3300
telemt_desync_frames_bucket_total{bucket="gt_10"} 4328
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6914
telemt_me_writer_restored_same_endpoint_total 6801
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1813355
telemt_user_connections_current{user="hello"} 1527
telemt_user_octets_from_client{user="hello"} 30736341860 (28.63 GB)
telemt_user_octets_to_client{user="hello"} 930352190512 (866.46 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 149
```