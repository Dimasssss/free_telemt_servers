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

# Server Metrics 2026-03-20 03:41:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 37442.6 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690141
telemt_connections_bad_total 48651
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15114
telemt_upstream_connect_attempt_total 7603
telemt_upstream_connect_success_total 7510
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 7603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4568
telemt_me_reconnect_success_total 4528
telemt_me_reader_eof_total 4789
telemt_me_idle_close_by_peer_total 4788
telemt_me_route_drop_no_conn_total 195132
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 546907
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2604
telemt_desync_full_logged_total 952
telemt_desync_suppressed_total 1652
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1121
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4568
telemt_me_writer_restored_same_endpoint_total 4515
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 548237
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 31255546572 (29.11 GB)
telemt_user_octets_to_client{user="hello"} 186801251189 (173.97 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 53898.1 (14h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3262644
telemt_connections_bad_total 202909
telemt_connections_current 2308
telemt_connections_me_current 2308
telemt_handshake_timeouts_total 70324
telemt_upstream_connect_attempt_total 10436
telemt_upstream_connect_success_total 10252
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 10436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10605
telemt_me_reconnect_success_total 6356
telemt_me_reader_eof_total 6800
telemt_me_idle_close_by_peer_total 6800
telemt_me_route_drop_no_conn_total 1555405
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2746407
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11640
telemt_desync_full_logged_total 3850
telemt_desync_suppressed_total 7790
telemt_desync_frames_bucket_total{bucket="1_2"} 2237
telemt_desync_frames_bucket_total{bucket="3_10"} 4536
telemt_desync_frames_bucket_total{bucket="gt_10"} 4867
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6564
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6301
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 2746118
telemt_user_connections_current{user="hello"} 2308
telemt_user_octets_from_client{user="hello"} 41664886882 (38.80 GB)
telemt_user_octets_to_client{user="hello"} 1026771200334 (956.26 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 309
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 53876.2 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3107798
telemt_connections_bad_total 482750
telemt_connections_current 1753
telemt_connections_me_current 1753
telemt_handshake_timeouts_total 49522
telemt_upstream_connect_attempt_total 8785
telemt_upstream_connect_success_total 8720
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6990
telemt_me_reconnect_success_total 6053
telemt_me_reader_eof_total 6365
telemt_me_idle_close_by_peer_total 6364
telemt_me_route_drop_no_conn_total 1973144
telemt_me_route_drop_channel_closed_total 175
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2157744
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8008
telemt_desync_full_logged_total 2456
telemt_desync_suppressed_total 5552
telemt_desync_frames_bucket_total{bucket="1_2"} 1965
telemt_desync_frames_bucket_total{bucket="3_10"} 3039
telemt_desync_frames_bucket_total{bucket="gt_10"} 3004
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6114
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6052
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 2152769
telemt_user_connections_current{user="hello"} 1753
telemt_user_octets_from_client{user="hello"} 32760407224 (30.51 GB)
telemt_user_octets_to_client{user="hello"} 841530846060 (783.74 GB)
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 53864.0 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2791839
telemt_connections_bad_total 215795
telemt_connections_current 1664
telemt_connections_me_current 1664
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33342
telemt_upstream_connect_attempt_total 58742
telemt_upstream_connect_success_total 54325
telemt_upstream_connect_fail_total 4417
telemt_upstream_connect_attempts_per_request{bucket="1"} 58742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4417
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9335
telemt_me_reconnect_success_total 6424
telemt_me_reader_eof_total 6694
telemt_me_idle_close_by_peer_total 6693
telemt_me_route_drop_no_conn_total 1927861
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2257649
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8721
telemt_desync_full_logged_total 2787
telemt_desync_suppressed_total 5934
telemt_desync_frames_bucket_total{bucket="1_2"} 2142
telemt_desync_frames_bucket_total{bucket="3_10"} 3184
telemt_desync_frames_bucket_total{bucket="gt_10"} 3395
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7098
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6420
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 2301292
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 36883822888 (34.35 GB)
telemt_user_octets_to_client{user="hello"} 669703558825 (623.71 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 107587.3 (29h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6500510
telemt_connections_bad_total 1125869
telemt_connections_current 1712
telemt_connections_me_current 1712
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 116490
telemt_upstream_connect_attempt_total 128785
telemt_upstream_connect_success_total 95493
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79493
telemt_me_reconnect_success_total 13819
telemt_me_reader_eof_total 14872
telemt_me_idle_close_by_peer_total 14858
telemt_me_route_drop_no_conn_total 2843967
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4581892
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
telemt_desync_total 19970
telemt_desync_full_logged_total 6348
telemt_desync_suppressed_total 13622
telemt_desync_frames_bucket_total{bucket="1_2"} 3528
telemt_desync_frames_bucket_total{bucket="3_10"} 8257
telemt_desync_frames_bucket_total{bucket="gt_10"} 8185
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 14135
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13794
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 4656962
telemt_user_connections_current{user="hello"} 1712
telemt_user_octets_from_client{user="hello"} 74023297028 (68.94 GB)
telemt_user_octets_to_client{user="hello"} 1812254858540 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 53827.2 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102958
telemt_connections_bad_total 94431
telemt_connections_current 662
telemt_connections_me_current 662
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13522
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
telemt_me_route_drop_no_conn_total 473056
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
telemt_user_connections_total{user="hello"} 940387
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 7978512583 (7.43 GB)
telemt_user_octets_to_client{user="hello"} 146602806154 (136.53 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 53828.6 (14h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2160824
telemt_connections_bad_total 128658
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_handshake_timeouts_total 40855
telemt_upstream_connect_attempt_total 9719
telemt_upstream_connect_success_total 9654
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7023
telemt_me_reconnect_success_total 6976
telemt_me_reader_eof_total 7367
telemt_me_idle_close_by_peer_total 7367
telemt_me_route_drop_no_conn_total 777006
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1838608
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9502
telemt_desync_full_logged_total 3066
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 1837
telemt_desync_frames_bucket_total{bucket="3_10"} 3327
telemt_desync_frames_bucket_total{bucket="gt_10"} 4338
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7074
telemt_me_writer_restored_same_endpoint_total 6959
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 1837707
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 31029427616 (28.90 GB)
telemt_user_octets_to_client{user="hello"} 946428980136 (881.43 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 175
```