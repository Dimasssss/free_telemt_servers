# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-23 05:36:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 116977.2 (32h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4156772
telemt_connections_bad_total 396004
telemt_connections_current 1574
telemt_connections_me_current 1574
telemt_handshake_timeouts_total 138069
telemt_upstream_connect_attempt_total 43500
telemt_upstream_connect_success_total 43499
telemt_upstream_connect_attempts_per_request{bucket="1"} 43499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1501
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 702
telemt_me_route_drop_no_conn_total 3433546
telemt_me_route_drop_channel_closed_total 1330
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3403037
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 829
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 914
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 14057
telemt_desync_full_logged_total 4464
telemt_desync_suppressed_total 9593
telemt_desync_frames_bucket_total{bucket="1_2"} 3653
telemt_desync_frames_bucket_total{bucket="3_10"} 5222
telemt_desync_frames_bucket_total{bucket="gt_10"} 5182
telemt_pool_swap_total 129
telemt_pool_force_close_total 3944
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 751
telemt_me_draining_writers_reap_progress_total 39855
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37284
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3879
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35911
telemt_me_writer_teardown_success_total{mode="normal"} 40133
telemt_me_writer_teardown_noop_total 39868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 434.104423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 751
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 3390467
telemt_user_connections_current{user="hello"} 1574
telemt_user_octets_from_client{user="hello"} 45310450192 (42.20 GB)
telemt_user_octets_to_client{user="hello"} 890130683204 (829.00 GB)
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 130358.1 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4156700
telemt_connections_bad_total 386350
telemt_connections_current 824
telemt_connections_me_current 824
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 107831
telemt_upstream_connect_attempt_total 81197
telemt_upstream_connect_success_total 80221
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 81086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10952
telemt_me_reconnect_success_total 3915
telemt_me_reader_eof_total 3885
telemt_me_idle_close_by_peer_total 3884
telemt_me_route_drop_no_conn_total 3671307
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3295962
telemt_me_endpoint_quarantine_total 1063
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 13555
telemt_desync_full_logged_total 7642
telemt_desync_suppressed_total 5913
telemt_desync_frames_bucket_total{bucket="1_2"} 3088
telemt_desync_frames_bucket_total{bucket="3_10"} 5313
telemt_desync_frames_bucket_total{bucket="gt_10"} 5154
telemt_pool_swap_total 123
telemt_pool_force_close_total 3417
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54604
telemt_me_writer_removed_unexpected_total 3807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6892
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51187
telemt_me_writer_teardown_success_total{mode="normal"} 58453
telemt_me_writer_teardown_noop_total 54605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113058
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.951612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113058
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3462
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 3310392
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 44503750139 (41.45 GB)
telemt_user_octets_to_client{user="hello"} 834558725541 (777.24 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 205203.1 (57h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16679879
telemt_connections_bad_total 1689649
telemt_connections_current 1905
telemt_connections_me_current 1905
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 408508
telemt_upstream_connect_attempt_total 92114
telemt_upstream_connect_success_total 92004
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3264
telemt_me_reconnect_success_total 1690
telemt_me_reader_eof_total 1651
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 14119651
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13250362
telemt_me_endpoint_quarantine_total 1393
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1553
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 41
telemt_desync_total 55304
telemt_desync_full_logged_total 17680
telemt_desync_suppressed_total 37624
telemt_desync_frames_bucket_total{bucket="1_2"} 12329
telemt_desync_frames_bucket_total{bucket="3_10"} 21677
telemt_desync_frames_bucket_total{bucket="gt_10"} 21298
telemt_pool_swap_total 222
telemt_pool_force_close_total 7120
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1102
telemt_me_draining_writers_reap_progress_total 70914
telemt_me_writer_removed_unexpected_total 1584
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5950
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65834
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63794
telemt_me_writer_teardown_success_total{mode="normal"} 71784
telemt_me_writer_teardown_noop_total 70968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.186981
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1102
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1464
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13250190
telemt_user_connections_current{user="hello"} 1905
telemt_user_octets_from_client{user="hello"} 200536434297 (186.76 GB)
telemt_user_octets_to_client{user="hello"} 3596906456651 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 205204.5 (57h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12185215
telemt_connections_bad_total 1292730
telemt_connections_current 951
telemt_connections_me_current 951
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 352890
telemt_upstream_connect_attempt_total 106528
telemt_upstream_connect_success_total 105116
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 106015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4712
telemt_me_reconnect_success_total 2024
telemt_me_reader_eof_total 1888
telemt_me_idle_close_by_peer_total 1888
telemt_me_route_drop_no_conn_total 4612928
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9011268
telemt_me_endpoint_quarantine_total 1397
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 39667
telemt_desync_full_logged_total 13384
telemt_desync_suppressed_total 26283
telemt_desync_frames_bucket_total{bucket="1_2"} 9844
telemt_desync_frames_bucket_total{bucket="3_10"} 15222
telemt_desync_frames_bucket_total{bucket="gt_10"} 14601
telemt_pool_swap_total 219
telemt_pool_force_close_total 6468
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 69023
telemt_me_writer_removed_unexpected_total 1918
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64757
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5956
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62555
telemt_me_writer_teardown_success_total{mode="normal"} 70804
telemt_me_writer_teardown_noop_total 69048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139852
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.692187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139852
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1729
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8948815
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 220437922556 (205.30 GB)
telemt_user_octets_to_client{user="hello"} 4033008022375 (3.67 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 205168.4 (56h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11333842
telemt_connections_bad_total 1040758
telemt_connections_current 1100
telemt_connections_me_current 1100
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 357969
telemt_upstream_connect_attempt_total 90965
telemt_upstream_connect_success_total 89388
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5903
telemt_me_reconnect_success_total 2486
telemt_me_reader_eof_total 2233
telemt_me_idle_close_by_peer_total 2232
telemt_me_route_drop_no_conn_total 5381738
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8519469
telemt_me_endpoint_quarantine_total 1449
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1533
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 38728
telemt_desync_full_logged_total 12865
telemt_desync_suppressed_total 25863
telemt_desync_frames_bucket_total{bucket="1_2"} 9774
telemt_desync_frames_bucket_total{bucket="3_10"} 14830
telemt_desync_frames_bucket_total{bucket="gt_10"} 14124
telemt_pool_swap_total 215
telemt_pool_force_close_total 6352
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69658
telemt_me_writer_removed_unexpected_total 2378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6793
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5781
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63306
telemt_me_writer_teardown_success_total{mode="normal"} 71973
telemt_me_writer_teardown_noop_total 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.975334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2167
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8511261
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 194276651707 (180.93 GB)
telemt_user_octets_to_client{user="hello"} 3530616518877 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 75448.5 (20h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11692717
telemt_connections_bad_total 706214
telemt_connections_current 1869
telemt_connections_me_current 1869
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 319281
telemt_upstream_connect_attempt_total 67623
telemt_upstream_connect_success_total 64042
telemt_upstream_connect_fail_total 2315
telemt_upstream_connect_attempts_per_request{bucket="1"} 66357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2315
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8413
telemt_me_reconnect_success_total 1559
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 985
telemt_me_route_drop_no_conn_total 25380462
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9662703
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 606
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 17345
telemt_desync_full_logged_total 4842
telemt_desync_suppressed_total 12503
telemt_desync_frames_bucket_total{bucket="1_2"} 3353
telemt_desync_frames_bucket_total{bucket="3_10"} 7093
telemt_desync_frames_bucket_total{bucket="gt_10"} 6899
telemt_pool_swap_total 77
telemt_pool_force_close_total 2413
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 25013
telemt_me_writer_removed_unexpected_total 1443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23177
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 342
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22600
telemt_me_writer_teardown_success_total{mode="normal"} 26408
telemt_me_writer_teardown_noop_total 25032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.056560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1000
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 9690232
telemt_user_connections_current{user="hello"} 1869
telemt_user_octets_from_client{user="hello"} 90938482939 (84.69 GB)
telemt_user_octets_to_client{user="hello"} 731103914349 (680.89 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 695
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 205175.0 (56h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11300560
telemt_connections_bad_total 992911
telemt_connections_current 1445
telemt_connections_me_current 1445
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 254341
telemt_upstream_connect_attempt_total 119875
telemt_upstream_connect_success_total 118633
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73531
telemt_me_reconnect_success_total 3262
telemt_me_reader_eof_total 2957
telemt_me_idle_close_by_peer_total 2954
telemt_me_route_drop_no_conn_total 5324907
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8897611
telemt_me_endpoint_quarantine_total 1391
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 47414
telemt_desync_full_logged_total 16299
telemt_desync_suppressed_total 31115
telemt_desync_frames_bucket_total{bucket="1_2"} 9640
telemt_desync_frames_bucket_total{bucket="3_10"} 18181
telemt_desync_frames_bucket_total{bucket="gt_10"} 19593
telemt_pool_swap_total 211
telemt_pool_force_close_total 6073
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 73717
telemt_me_writer_removed_unexpected_total 2974
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67644
telemt_me_writer_teardown_success_total{mode="normal"} 76738
telemt_me_writer_teardown_noop_total 73718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150456
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.364580
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150456
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2747
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8900243
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 199257609541 (185.57 GB)
telemt_user_octets_to_client{user="hello"} 3407310343088 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 142026.3 (39h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12089123
telemt_connections_bad_total 494121
telemt_connections_current 1256
telemt_connections_me_current 1256
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4877929
telemt_upstream_connect_attempt_total 68914
telemt_upstream_connect_success_total 68424
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 68901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49369
telemt_me_reconnect_success_total 1971
telemt_me_reader_eof_total 1656
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 4146767
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5809469
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1097
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32689
telemt_desync_full_logged_total 11184
telemt_desync_suppressed_total 21505
telemt_desync_frames_bucket_total{bucket="1_2"} 6572
telemt_desync_frames_bucket_total{bucket="3_10"} 12868
telemt_desync_frames_bucket_total{bucket="gt_10"} 13249
telemt_pool_swap_total 151
telemt_pool_force_close_total 4265
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 53701
telemt_me_writer_removed_unexpected_total 1693
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3821
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49436
telemt_me_writer_teardown_success_total{mode="normal"} 55452
telemt_me_writer_teardown_noop_total 53708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.836498
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 1741
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5801309
telemt_user_connections_current{user="hello"} 1256
telemt_user_octets_from_client{user="hello"} 121885457024 (113.51 GB)
telemt_user_octets_to_client{user="hello"} 2258297171846 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 122997.0 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1706072
telemt_connections_bad_total 37606
telemt_connections_current 852
telemt_connections_me_current 852
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37014
telemt_upstream_connect_attempt_total 57910
telemt_upstream_connect_success_total 57718
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 57872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2517
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_route_drop_no_conn_total 575829
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1515154
telemt_me_endpoint_quarantine_total 1046
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1016
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 10427
telemt_desync_full_logged_total 2946
telemt_desync_suppressed_total 7481
telemt_desync_frames_bucket_total{bucket="1_2"} 3298
telemt_desync_frames_bucket_total{bucket="3_10"} 3904
telemt_desync_frames_bucket_total{bucket="gt_10"} 3225
telemt_pool_swap_total 133
telemt_pool_force_close_total 3361
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49368
telemt_me_writer_removed_unexpected_total 981
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3730
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46665
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46007
telemt_me_writer_teardown_success_total{mode="normal"} 50395
telemt_me_writer_teardown_noop_total 49372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.712464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 877
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1510712
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 27709203705 (25.81 GB)
telemt_user_octets_to_client{user="hello"} 617125217683 (574.74 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 205179.8 (56h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13581175
telemt_connections_bad_total 1639808
telemt_connections_current 1494
telemt_connections_me_current 1494
telemt_handshake_timeouts_total 398192
telemt_upstream_connect_attempt_total 82761
telemt_upstream_connect_success_total 82395
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 82624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3250
telemt_me_reconnect_success_total 1628
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 4533319
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10242466
telemt_me_endpoint_quarantine_total 1515
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 43016
telemt_desync_full_logged_total 14031
telemt_desync_suppressed_total 28985
telemt_desync_frames_bucket_total{bucket="1_2"} 10469
telemt_desync_frames_bucket_total{bucket="3_10"} 15795
telemt_desync_frames_bucket_total{bucket="gt_10"} 16752
telemt_pool_swap_total 227
telemt_pool_force_close_total 5925
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 703
telemt_me_draining_writers_reap_progress_total 74924
telemt_me_writer_removed_unexpected_total 1548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68999
telemt_me_writer_teardown_success_total{mode="normal"} 76533
telemt_me_writer_teardown_noop_total 74926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151459
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.992913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151459
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 703
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1432
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 10208873
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 197123653460 (183.59 GB)
telemt_user_octets_to_client{user="hello"} 4553922081488 (4.14 TB)
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 205176.1 (56h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11895753
telemt_connections_bad_total 1388492
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 320315
telemt_upstream_connect_attempt_total 110663
telemt_upstream_connect_success_total 109713
telemt_upstream_connect_fail_total 741
telemt_upstream_connect_attempts_per_request{bucket="1"} 110454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 741
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11119
telemt_me_reconnect_success_total 2766
telemt_me_reader_eof_total 2571
telemt_me_idle_close_by_peer_total 2570
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5701102
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9163119
telemt_me_endpoint_quarantine_total 1693
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1563
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 42637
telemt_desync_full_logged_total 13733
telemt_desync_suppressed_total 28904
telemt_desync_frames_bucket_total{bucket="1_2"} 11078
telemt_desync_frames_bucket_total{bucket="3_10"} 15659
telemt_desync_frames_bucket_total{bucket="gt_10"} 15900
telemt_pool_swap_total 217
telemt_pool_force_close_total 5675
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 75314
telemt_me_writer_removed_unexpected_total 2605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5204
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69639
telemt_me_writer_teardown_success_total{mode="normal"} 78021
telemt_me_writer_teardown_noop_total 75319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.842327
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2206
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9167548
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 159666303392 (148.70 GB)
telemt_user_octets_to_client{user="hello"} 3589766331378 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 523
telemt_user_unique_ips_recent_window{user="hello"} 197
```