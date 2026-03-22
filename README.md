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

# Server Metrics 2026-03-22 07:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36025.2 (10h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730675
telemt_connections_bad_total 46841
telemt_connections_current 1900
telemt_connections_me_current 1900
telemt_handshake_timeouts_total 34786
telemt_upstream_connect_attempt_total 14631
telemt_upstream_connect_success_total 14630
telemt_upstream_connect_attempts_per_request{bucket="1"} 14630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 381
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 226
telemt_me_idle_close_by_peer_total 226
telemt_me_route_drop_no_conn_total 266210
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604986
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_warm_current 4
telemt_desync_total 4948
telemt_desync_full_logged_total 1384
telemt_desync_suppressed_total 3564
telemt_desync_frames_bucket_total{bucket="1_2"} 1607
telemt_desync_frames_bucket_total{bucket="3_10"} 1846
telemt_desync_frames_bucket_total{bucket="gt_10"} 1495
telemt_pool_swap_total 39
telemt_pool_force_close_total 1048
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 13242
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12194
telemt_me_writer_teardown_success_total{mode="normal"} 13452
telemt_me_writer_teardown_noop_total 13243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.123324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 603826
telemt_user_connections_current{user="hello"} 1900
telemt_user_octets_from_client{user="hello"} 8342571112 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 208111352428 (193.82 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 376
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49391.5 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1208353
telemt_connections_bad_total 119548
telemt_connections_current 1367
telemt_connections_me_current 1367
telemt_handshake_timeouts_total 38216
telemt_upstream_connect_attempt_total 26073
telemt_upstream_connect_success_total 25690
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 26022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1927
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 451622
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910047
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 3894
telemt_desync_full_logged_total 2282
telemt_desync_suppressed_total 1612
telemt_desync_frames_bucket_total{bucket="1_2"} 818
telemt_desync_frames_bucket_total{bucket="3_10"} 1506
telemt_desync_frames_bucket_total{bucket="gt_10"} 1570
telemt_pool_swap_total 52
telemt_pool_force_close_total 1389
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 20312
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19152
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18923
telemt_me_writer_teardown_success_total{mode="normal"} 20940
telemt_me_writer_teardown_noop_total 20312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41252
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.283216
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41252
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 911815
telemt_user_connections_current{user="hello"} 1367
telemt_user_octets_from_client{user="hello"} 14640524150 (13.64 GB)
telemt_user_octets_to_client{user="hello"} 337132601299 (313.98 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 427
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 124251.5 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8905069
telemt_connections_bad_total 822009
telemt_connections_current 4574
telemt_connections_me_current 4574
telemt_handshake_timeouts_total 279584
telemt_upstream_connect_attempt_total 45958
telemt_upstream_connect_success_total 45880
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1752
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 916
telemt_me_idle_close_by_peer_total 916
telemt_me_route_drop_no_conn_total 4841335
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7024457
telemt_me_endpoint_quarantine_total 788
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 933
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 18
telemt_desync_total 30301
telemt_desync_full_logged_total 10035
telemt_desync_suppressed_total 20266
telemt_desync_frames_bucket_total{bucket="1_2"} 6582
telemt_desync_frames_bucket_total{bucket="3_10"} 11791
telemt_desync_frames_bucket_total{bucket="gt_10"} 11928
telemt_pool_swap_total 134
telemt_pool_force_close_total 4425
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 41925
telemt_me_writer_removed_unexpected_total 881
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3481
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37500
telemt_me_writer_teardown_success_total{mode="normal"} 42305
telemt_me_writer_teardown_noop_total 41969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84274
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 176.430038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84274
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 7015314
telemt_user_connections_current{user="hello"} 4574
telemt_user_octets_from_client{user="hello"} 118554055096 (110.41 GB)
telemt_user_octets_to_client{user="hello"} 2400325202564 (2.18 TB)
telemt_user_unique_ips_current{user="hello"} 1849
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 124252.9 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7334192
telemt_connections_bad_total 647029
telemt_connections_current 4644
telemt_connections_me_current 4644
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 241773
telemt_upstream_connect_attempt_total 49975
telemt_upstream_connect_success_total 49569
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2626
telemt_me_reconnect_success_total 985
telemt_me_reader_eof_total 951
telemt_me_idle_close_by_peer_total 951
telemt_me_route_drop_no_conn_total 2468936
telemt_me_route_drop_channel_closed_total 301
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5434628
telemt_me_endpoint_quarantine_total 786
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 954
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 20
telemt_desync_total 24978
telemt_desync_full_logged_total 8589
telemt_desync_suppressed_total 16389
telemt_desync_frames_bucket_total{bucket="1_2"} 5985
telemt_desync_frames_bucket_total{bucket="3_10"} 9697
telemt_desync_frames_bucket_total{bucket="gt_10"} 9296
telemt_pool_swap_total 135
telemt_pool_force_close_total 4026
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 40394
telemt_me_writer_removed_unexpected_total 928
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37909
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36368
telemt_me_writer_teardown_success_total{mode="normal"} 41251
telemt_me_writer_teardown_noop_total 40400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81651
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.889748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81651
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 861
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5355749
telemt_user_connections_current{user="hello"} 4644
telemt_user_octets_from_client{user="hello"} 152505464281 (142.03 GB)
telemt_user_octets_to_client{user="hello"} 2591852769511 (2.36 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1827
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 124220.2 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7090705
telemt_connections_bad_total 587589
telemt_connections_current 3336
telemt_connections_me_current 3336
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236864
telemt_upstream_connect_attempt_total 56395
telemt_upstream_connect_success_total 55759
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 55904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1257
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2655
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 1053
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 2680563
telemt_me_route_drop_channel_closed_total 163
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5283802
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 919
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24864
telemt_desync_full_logged_total 8449
telemt_desync_suppressed_total 16415
telemt_desync_frames_bucket_total{bucket="1_2"} 6034
telemt_desync_frames_bucket_total{bucket="3_10"} 9527
telemt_desync_frames_bucket_total{bucket="gt_10"} 9303
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 41286
telemt_me_writer_removed_unexpected_total 1044
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3603
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38741
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37391
telemt_me_writer_teardown_success_total{mode="normal"} 42344
telemt_me_writer_teardown_noop_total 41298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83642
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.520852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83642
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 974
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5277622
telemt_user_connections_current{user="hello"} 3336
telemt_user_octets_from_client{user="hello"} 141681578867 (131.95 GB)
telemt_user_octets_to_client{user="hello"} 2375690526175 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1356
telemt_user_unique_ips_recent_window{user="hello"} 712
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 124256.2 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22688290
telemt_connections_bad_total 1906226
telemt_connections_current 6373
telemt_connections_me_current 6373
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 675364
telemt_upstream_connect_attempt_total 238708
telemt_upstream_connect_success_total 219079
telemt_upstream_connect_fail_total 17675
telemt_upstream_connect_attempts_per_request{bucket="1"} 236754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17675
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66394
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 43141333
telemt_me_route_drop_channel_closed_total 136
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18259727
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 967
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 973
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_me_writers_warm_current 11
telemt_desync_total 35301
telemt_desync_full_logged_total 10591
telemt_desync_suppressed_total 24710
telemt_desync_frames_bucket_total{bucket="1_2"} 7838
telemt_desync_frames_bucket_total{bucket="3_10"} 15595
telemt_desync_frames_bucket_total{bucket="gt_10"} 11868
telemt_pool_swap_total 128
telemt_pool_force_close_total 4057
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 927
telemt_me_draining_writers_reap_progress_total 38858
telemt_me_writer_removed_unexpected_total 2428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5250
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 579
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34801
telemt_me_writer_teardown_success_total{mode="normal"} 41017
telemt_me_writer_teardown_noop_total 38888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.586364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 927
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1785
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18424469
telemt_user_connections_current{user="hello"} 6373
telemt_user_octets_from_client{user="hello"} 269443500391 (250.94 GB)
telemt_user_octets_to_client{user="hello"} 1395133296326 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 2123
telemt_user_unique_ips_recent_window{user="hello"} 1093
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 124223.7 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6790059
telemt_connections_bad_total 626115
telemt_connections_current 4117
telemt_connections_me_current 4117
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 140578
telemt_upstream_connect_attempt_total 64990
telemt_upstream_connect_success_total 64248
telemt_upstream_connect_fail_total 636
telemt_upstream_connect_attempts_per_request{bucket="1"} 64884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 636
telemt_me_reconnect_attempts_total 70002
telemt_me_reconnect_success_total 1920
telemt_me_reader_eof_total 1697
telemt_me_idle_close_by_peer_total 1696
telemt_me_route_drop_no_conn_total 2603689
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5308721
telemt_me_endpoint_quarantine_total 830
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 941
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_active_current 47
telemt_desync_total 26618
telemt_desync_full_logged_total 9260
telemt_desync_suppressed_total 17358
telemt_desync_frames_bucket_total{bucket="1_2"} 5323
telemt_desync_frames_bucket_total{bucket="3_10"} 10219
telemt_desync_frames_bucket_total{bucket="gt_10"} 11076
telemt_pool_swap_total 129
telemt_pool_force_close_total 3700
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 43550
telemt_me_writer_removed_unexpected_total 1728
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40954
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3290
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39850
telemt_me_writer_teardown_success_total{mode="normal"} 45315
telemt_me_writer_teardown_noop_total 43551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88866
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.919135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88866
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5300128
telemt_user_connections_current{user="hello"} 4117
telemt_user_octets_from_client{user="hello"} 135787523400 (126.46 GB)
telemt_user_octets_to_client{user="hello"} 2217914946710 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1648
telemt_user_unique_ips_recent_window{user="hello"} 569
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61059.8 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4997525
telemt_connections_bad_total 202684
telemt_connections_current 3614
telemt_connections_me_current 3614
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1975216
telemt_upstream_connect_attempt_total 33864
telemt_upstream_connect_success_total 33633
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 33857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_reconnect_attempts_total 46195
telemt_me_reconnect_success_total 1072
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 1227923
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2492341
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13322
telemt_desync_full_logged_total 4591
telemt_desync_suppressed_total 8731
telemt_desync_frames_bucket_total{bucket="1_2"} 2640
telemt_desync_frames_bucket_total{bucket="3_10"} 5091
telemt_desync_frames_bucket_total{bucket="gt_10"} 5591
telemt_pool_swap_total 66
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 22274
telemt_me_writer_removed_unexpected_total 832
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1875
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21253
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20333
telemt_me_writer_teardown_success_total{mode="normal"} 23128
telemt_me_writer_teardown_noop_total 22276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45404
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.867900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45404
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 956
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2494126
telemt_user_connections_current{user="hello"} 3614
telemt_user_octets_from_client{user="hello"} 64351909692 (59.93 GB)
telemt_user_octets_to_client{user="hello"} 1107213468946 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1547
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42030.3 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321426
telemt_connections_bad_total 2257
telemt_connections_current 722
telemt_connections_me_current 722
telemt_handshake_timeouts_total 7355
telemt_upstream_connect_attempt_total 20176
telemt_upstream_connect_success_total 20124
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 20172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 96054
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290859
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 47
telemt_desync_total 1398
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 394
telemt_pool_swap_total 46
telemt_pool_force_close_total 1032
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18249
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17345
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17217
telemt_me_writer_teardown_success_total{mode="normal"} 18537
telemt_me_writer_teardown_noop_total 18249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36786
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.477655
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36786
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 251
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 290438
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 4798977004 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 165031437720 (153.70 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 124228.0 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8278467
telemt_connections_bad_total 875131
telemt_connections_current 4474
telemt_connections_me_current 4474
telemt_handshake_timeouts_total 233147
telemt_upstream_connect_attempt_total 48712
telemt_upstream_connect_success_total 48532
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 48673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1793
telemt_me_reconnect_success_total 967
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 949
telemt_me_route_drop_no_conn_total 2330208
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6159916
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 948
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_warm_current 2
telemt_desync_total 24611
telemt_desync_full_logged_total 8074
telemt_desync_suppressed_total 16537
telemt_desync_frames_bucket_total{bucket="1_2"} 6104
telemt_desync_frames_bucket_total{bucket="3_10"} 8985
telemt_desync_frames_bucket_total{bucket="gt_10"} 9522
telemt_pool_swap_total 137
telemt_pool_force_close_total 3658
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 43976
telemt_me_writer_removed_unexpected_total 912
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40318
telemt_me_writer_teardown_success_total{mode="normal"} 44915
telemt_me_writer_teardown_noop_total 43978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.366463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6133862
telemt_user_connections_current{user="hello"} 4474
telemt_user_octets_from_client{user="hello"} 120631050640 (112.35 GB)
telemt_user_octets_to_client{user="hello"} 2878007621600 (2.62 TB)
telemt_user_unique_ips_current{user="hello"} 1779
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 124225.0 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7229789
telemt_connections_bad_total 751950
telemt_connections_current 3883
telemt_connections_me_current 3883
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 193109
telemt_upstream_connect_attempt_total 64497
telemt_upstream_connect_success_total 64006
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 64434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_reconnect_attempts_total 5919
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1196
telemt_me_idle_close_by_peer_total 1196
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2394320
telemt_me_route_drop_channel_closed_total 198
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5516512
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 947
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 42
telemt_desync_total 23471
telemt_desync_full_logged_total 7800
telemt_desync_suppressed_total 15671
telemt_desync_frames_bucket_total{bucket="1_2"} 5816
telemt_desync_frames_bucket_total{bucket="3_10"} 8620
telemt_desync_frames_bucket_total{bucket="gt_10"} 9035
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 42456
telemt_me_writer_removed_unexpected_total 1211
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4005
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39723
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38846
telemt_me_writer_teardown_success_total{mode="normal"} 43728
telemt_me_writer_teardown_noop_total 42460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.447420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 264
telemt_me_writer_restored_same_endpoint_total 1035
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 5518361
telemt_user_connections_current{user="hello"} 3883
telemt_user_octets_from_client{user="hello"} 102208566277 (95.19 GB)
telemt_user_octets_to_client{user="hello"} 2397383327000 (2.18 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1602
telemt_user_unique_ips_recent_window{user="hello"} 487
```