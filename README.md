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

# Server Metrics 2026-03-23 06:16:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 119435.1 (33h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4286136
telemt_connections_bad_total 407130
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_handshake_timeouts_total 145348
telemt_upstream_connect_attempt_total 44330
telemt_upstream_connect_success_total 44329
telemt_upstream_connect_attempts_per_request{bucket="1"} 44329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 719
telemt_me_idle_close_by_peer_total 719
telemt_me_route_drop_no_conn_total 3564308
telemt_me_route_drop_channel_closed_total 1375
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3508314
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 849
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 936
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
telemt_me_writers_active_current 44
telemt_desync_total 14558
telemt_desync_full_logged_total 4606
telemt_desync_suppressed_total 9952
telemt_desync_frames_bucket_total{bucket="1_2"} 3759
telemt_desync_frames_bucket_total{bucket="3_10"} 5433
telemt_desync_frames_bucket_total{bucket="gt_10"} 5366
telemt_pool_swap_total 132
telemt_pool_force_close_total 4069
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 777
telemt_me_draining_writers_reap_progress_total 40640
telemt_me_writer_removed_unexpected_total 691
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37987
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3999
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36571
telemt_me_writer_teardown_success_total{mode="normal"} 40903
telemt_me_writer_teardown_noop_total 40653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 449.229646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 777
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 3495492
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 46270763524 (43.09 GB)
telemt_user_octets_to_client{user="hello"} 911543053424 (848.94 GB)
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 132801.1 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4202044
telemt_connections_bad_total 390809
telemt_connections_current 653
telemt_connections_me_current 653
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 110746
telemt_upstream_connect_attempt_total 82527
telemt_upstream_connect_success_total 81536
telemt_upstream_connect_fail_total 879
telemt_upstream_connect_attempts_per_request{bucket="1"} 82415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 879
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11088
telemt_me_reconnect_success_total 3980
telemt_me_reader_eof_total 3948
telemt_me_idle_close_by_peer_total 3947
telemt_me_route_drop_no_conn_total 3683526
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3332144
telemt_me_endpoint_quarantine_total 1084
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1047
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
telemt_me_writers_active_current 44
telemt_desync_total 13758
telemt_desync_full_logged_total 7761
telemt_desync_suppressed_total 5997
telemt_desync_frames_bucket_total{bucket="1_2"} 3122
telemt_desync_frames_bucket_total{bucket="3_10"} 5396
telemt_desync_frames_bucket_total{bucket="gt_10"} 5240
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 55786
telemt_me_writer_removed_unexpected_total 3869
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7013
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52686
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52294
telemt_me_writer_teardown_success_total{mode="normal"} 59699
telemt_me_writer_teardown_noop_total 55787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.021492
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 3520
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 3346484
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 45066503611 (41.97 GB)
telemt_user_octets_to_client{user="hello"} 847657351625 (789.44 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 207661.1 (57h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16787679
telemt_connections_bad_total 1705009
telemt_connections_current 2014
telemt_connections_me_current 2014
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 414054
telemt_upstream_connect_attempt_total 93095
telemt_upstream_connect_success_total 92983
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1734
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3277
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1661
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 14146194
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13333998
telemt_me_endpoint_quarantine_total 1412
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1573
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
telemt_me_writers_active_current 45
telemt_desync_total 55867
telemt_desync_full_logged_total 17850
telemt_desync_suppressed_total 38017
telemt_desync_frames_bucket_total{bucket="1_2"} 12430
telemt_desync_frames_bucket_total{bucket="3_10"} 21870
telemt_desync_frames_bucket_total{bucket="gt_10"} 21567
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1114
telemt_me_draining_writers_reap_progress_total 71796
telemt_me_writer_removed_unexpected_total 1594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64596
telemt_me_writer_teardown_success_total{mode="normal"} 72676
telemt_me_writer_teardown_noop_total 71850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 142865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144526
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.960037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144526
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1114
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1474
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13333748
telemt_user_connections_current{user="hello"} 2014
telemt_user_octets_from_client{user="hello"} 201656568533 (187.81 GB)
telemt_user_octets_to_client{user="hello"} 3630076032375 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 207662.3 (57h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12259643
telemt_connections_bad_total 1305623
telemt_connections_current 1327
telemt_connections_me_current 1327
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 355396
telemt_upstream_connect_attempt_total 107548
telemt_upstream_connect_success_total 106133
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 107034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4764
telemt_me_reconnect_success_total 2054
telemt_me_reader_eof_total 1909
telemt_me_idle_close_by_peer_total 1909
telemt_me_route_drop_no_conn_total 4629141
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9063156
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1589
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_desync_total 39886
telemt_desync_full_logged_total 13486
telemt_desync_suppressed_total 26400
telemt_desync_frames_bucket_total{bucket="1_2"} 9888
telemt_desync_frames_bucket_total{bucket="3_10"} 15308
telemt_desync_frames_bucket_total{bucket="gt_10"} 14690
telemt_pool_swap_total 222
telemt_pool_force_close_total 6553
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 69956
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6130
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65628
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63403
telemt_me_writer_teardown_success_total{mode="normal"} 71758
telemt_me_writer_teardown_noop_total 69981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 140547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141739
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.107196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141739
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1750
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9000653
telemt_user_connections_current{user="hello"} 1327
telemt_user_octets_from_client{user="hello"} 220966728756 (205.79 GB)
telemt_user_octets_to_client{user="hello"} 4051082115791 (3.68 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 207626.5 (57h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11400696
telemt_connections_bad_total 1049748
telemt_connections_current 1164
telemt_connections_me_current 1164
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 361859
telemt_upstream_connect_attempt_total 91952
telemt_upstream_connect_success_total 90372
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5931
telemt_me_reconnect_success_total 2515
telemt_me_reader_eof_total 2252
telemt_me_idle_close_by_peer_total 2251
telemt_me_route_drop_no_conn_total 5399037
telemt_me_route_drop_channel_closed_total 387
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8568935
telemt_me_endpoint_quarantine_total 1472
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1554
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 39013
telemt_desync_full_logged_total 12968
telemt_desync_suppressed_total 26045
telemt_desync_frames_bucket_total{bucket="1_2"} 9838
telemt_desync_frames_bucket_total{bucket="3_10"} 14932
telemt_desync_frames_bucket_total{bucket="gt_10"} 14243
telemt_pool_swap_total 218
telemt_pool_force_close_total 6444
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 766
telemt_me_draining_writers_reap_progress_total 70562
telemt_me_writer_removed_unexpected_total 2397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6877
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64118
telemt_me_writer_teardown_success_total{mode="normal"} 72896
telemt_me_writer_teardown_noop_total 70633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 137631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 140382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.320690
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 766
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2184
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 8560670
telemt_user_connections_current{user="hello"} 1164
telemt_user_octets_from_client{user="hello"} 194757656031 (181.38 GB)
telemt_user_octets_to_client{user="hello"} 3552111416609 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 77906.5 (21h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11833540
telemt_connections_bad_total 718606
telemt_connections_current 2280
telemt_connections_me_current 2280
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 333049
telemt_upstream_connect_attempt_total 72377
telemt_upstream_connect_success_total 68633
telemt_upstream_connect_fail_total 2454
telemt_upstream_connect_attempts_per_request{bucket="1"} 71087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2454
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8583
telemt_me_reconnect_success_total 1595
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 25423097
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9762917
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 112
telemt_me_single_endpoint_outage_exit_total 112
telemt_me_single_endpoint_outage_reconnect_attempt_total 214
telemt_me_single_endpoint_outage_reconnect_success_total 57
telemt_me_single_endpoint_quarantine_bypass_total 214
telemt_me_single_endpoint_shadow_rotate_total 626
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
telemt_me_writers_active_current 47
telemt_desync_total 17524
telemt_desync_full_logged_total 4924
telemt_desync_suppressed_total 12600
telemt_desync_frames_bucket_total{bucket="1_2"} 3395
telemt_desync_frames_bucket_total{bucket="3_10"} 7173
telemt_desync_frames_bucket_total{bucket="gt_10"} 6956
telemt_pool_swap_total 80
telemt_pool_force_close_total 2473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 25858
telemt_me_writer_removed_unexpected_total 1471
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3340
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23934
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23385
telemt_me_writer_teardown_success_total{mode="normal"} 27274
telemt_me_writer_teardown_noop_total 25877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53151
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.375547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53151
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9794100
telemt_user_connections_current{user="hello"} 2280
telemt_user_octets_from_client{user="hello"} 92014053832 (85.69 GB)
telemt_user_octets_to_client{user="hello"} 765710797744 (713.12 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 207633.1 (57h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11390496
telemt_connections_bad_total 1004361
telemt_connections_current 1787
telemt_connections_me_current 1787
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 259371
telemt_upstream_connect_attempt_total 121189
telemt_upstream_connect_success_total 119893
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 121011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73750
telemt_me_reconnect_success_total 3352
telemt_me_reader_eof_total 3028
telemt_me_idle_close_by_peer_total 3025
telemt_me_route_drop_no_conn_total 5348510
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8963911
telemt_me_endpoint_quarantine_total 1419
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1581
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 88
telemt_desync_total 47638
telemt_desync_full_logged_total 16394
telemt_desync_suppressed_total 31244
telemt_desync_frames_bucket_total{bucket="1_2"} 9694
telemt_desync_frames_bucket_total{bucket="3_10"} 18255
telemt_desync_frames_bucket_total{bucket="gt_10"} 19689
telemt_pool_swap_total 213
telemt_pool_force_close_total 6123
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 74815
telemt_me_writer_removed_unexpected_total 3045
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7446
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5373
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 750
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68692
telemt_me_writer_teardown_success_total{mode="normal"} 77907
telemt_me_writer_teardown_noop_total 74816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152723
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.397064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152723
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2820
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8966476
telemt_user_connections_current{user="hello"} 1787
telemt_user_octets_from_client{user="hello"} 199984337961 (186.25 GB)
telemt_user_octets_to_client{user="hello"} 3434797746644 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 721
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 144469.4 (40h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12197893
telemt_connections_bad_total 502391
telemt_connections_current 1138
telemt_connections_me_current 1138
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4911566
telemt_upstream_connect_attempt_total 69980
telemt_upstream_connect_success_total 69482
telemt_upstream_connect_fail_total 485
telemt_upstream_connect_attempts_per_request{bucket="1"} 69967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 485
telemt_me_reconnect_attempts_total 49453
telemt_me_reconnect_success_total 2006
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1682
telemt_me_route_drop_no_conn_total 4164557
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5861894
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1115
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33013
telemt_desync_full_logged_total 11315
telemt_desync_suppressed_total 21698
telemt_desync_frames_bucket_total{bucket="1_2"} 6638
telemt_desync_frames_bucket_total{bucket="3_10"} 13003
telemt_desync_frames_bucket_total{bucket="gt_10"} 13372
telemt_pool_swap_total 154
telemt_pool_force_close_total 4334
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 399
telemt_me_draining_writers_reap_progress_total 54654
telemt_me_writer_removed_unexpected_total 1720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52098
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50320
telemt_me_writer_teardown_success_total{mode="normal"} 56432
telemt_me_writer_teardown_noop_total 54661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.943564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 399
telemt_me_refill_failed_total 2756
telemt_me_writer_restored_same_endpoint_total 1772
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5853716
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 122550997532 (114.13 GB)
telemt_user_octets_to_client{user="hello"} 2281216634558 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 125440.1 (34h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1782683
telemt_connections_bad_total 37717
telemt_connections_current 1062
telemt_connections_me_current 1062
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 39557
telemt_upstream_connect_attempt_total 58822
telemt_upstream_connect_success_total 58625
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 58783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2559
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1031
telemt_me_idle_close_by_peer_total 1031
telemt_me_route_drop_no_conn_total 664727
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1583880
telemt_me_endpoint_quarantine_total 1067
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1034
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
telemt_me_writers_active_current 44
telemt_desync_total 10655
telemt_desync_full_logged_total 3009
telemt_desync_suppressed_total 7646
telemt_desync_frames_bucket_total{bucket="1_2"} 3385
telemt_desync_frames_bucket_total{bucket="3_10"} 3992
telemt_desync_frames_bucket_total{bucket="gt_10"} 3278
telemt_pool_swap_total 136
telemt_pool_force_close_total 3443
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 50208
telemt_me_writer_removed_unexpected_total 993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3789
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47460
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3355
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46765
telemt_me_writer_teardown_success_total{mode="normal"} 51249
telemt_me_writer_teardown_noop_total 50212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101461
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.742001
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101461
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1579391
telemt_user_connections_current{user="hello"} 1062
telemt_user_octets_from_client{user="hello"} 28170922373 (26.24 GB)
telemt_user_octets_to_client{user="hello"} 626207174311 (583.20 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 207637.7 (57h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13676185
telemt_connections_bad_total 1665525
telemt_connections_current 1600
telemt_connections_me_current 1600
telemt_handshake_timeouts_total 400734
telemt_upstream_connect_attempt_total 83803
telemt_upstream_connect_success_total 83434
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 83666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3304
telemt_me_reconnect_success_total 1651
telemt_me_reader_eof_total 1642
telemt_me_idle_close_by_peer_total 1642
telemt_me_route_drop_no_conn_total 4551121
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10306808
telemt_me_endpoint_quarantine_total 1539
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1580
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
telemt_desync_total 43409
telemt_desync_full_logged_total 14131
telemt_desync_suppressed_total 29278
telemt_desync_frames_bucket_total{bucket="1_2"} 10549
telemt_desync_frames_bucket_total{bucket="3_10"} 15972
telemt_desync_frames_bucket_total{bucket="gt_10"} 16888
telemt_pool_swap_total 230
telemt_pool_force_close_total 5993
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 75853
telemt_me_writer_removed_unexpected_total 1570
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5819
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69860
telemt_me_writer_teardown_success_total{mode="normal"} 77485
telemt_me_writer_teardown_noop_total 75855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 150661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 152831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.151349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1450
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10273125
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 197709587192 (184.13 GB)
telemt_user_octets_to_client{user="hello"} 4583538802412 (4.17 TB)
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 207634.3 (57h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11982828
telemt_connections_bad_total 1405851
telemt_connections_current 1427
telemt_connections_me_current 1427
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 322196
telemt_upstream_connect_attempt_total 111818
telemt_upstream_connect_success_total 110859
telemt_upstream_connect_fail_total 750
telemt_upstream_connect_attempts_per_request{bucket="1"} 111609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 750
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11174
telemt_me_reconnect_success_total 2796
telemt_me_reader_eof_total 2589
telemt_me_idle_close_by_peer_total 2588
telemt_me_seq_mismatch_total 112
telemt_me_route_drop_no_conn_total 5720480
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9227085
telemt_me_endpoint_quarantine_total 1723
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 60
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
telemt_me_writers_active_current 52
telemt_desync_total 43304
telemt_desync_full_logged_total 13843
telemt_desync_suppressed_total 29461
telemt_desync_frames_bucket_total{bucket="1_2"} 11232
telemt_desync_frames_bucket_total{bucket="3_10"} 15996
telemt_desync_frames_bucket_total{bucket="gt_10"} 16076
telemt_pool_swap_total 220
telemt_pool_force_close_total 5734
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 76372
telemt_me_writer_removed_unexpected_total 2626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70638
telemt_me_writer_teardown_success_total{mode="normal"} 79102
telemt_me_writer_teardown_noop_total 76377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 152735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 154556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 155110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 155429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 155479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 155479
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.870719
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 155479
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 147
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 9231339
telemt_user_connections_current{user="hello"} 1427
telemt_user_octets_from_client{user="hello"} 160374363652 (149.36 GB)
telemt_user_octets_to_client{user="hello"} 3612364482130 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 212
```