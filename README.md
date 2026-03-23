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

# Server Metrics 2026-03-23 03:48:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 110535.4 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3770097
telemt_connections_bad_total 367323
telemt_connections_current 1149
telemt_connections_me_current 1149
telemt_handshake_timeouts_total 124307
telemt_upstream_connect_attempt_total 41206
telemt_upstream_connect_success_total 41205
telemt_upstream_connect_attempts_per_request{bucket="1"} 41205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1438
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 655
telemt_me_idle_close_by_peer_total 655
telemt_me_route_drop_no_conn_total 3020795
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3074406
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 864
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 13146
telemt_desync_full_logged_total 4179
telemt_desync_suppressed_total 8967
telemt_desync_frames_bucket_total{bucket="1_2"} 3475
telemt_desync_frames_bucket_total{bucket="3_10"} 4813
telemt_desync_frames_bucket_total{bucket="gt_10"} 4858
telemt_pool_swap_total 122
telemt_pool_force_close_total 3715
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 678
telemt_me_draining_writers_reap_progress_total 37753
telemt_me_writer_removed_unexpected_total 632
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2691
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35342
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34038
telemt_me_writer_teardown_success_total{mode="normal"} 38033
telemt_me_writer_teardown_noop_total 37764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 380.519077
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 678
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3063246
telemt_user_connections_current{user="hello"} 1149
telemt_user_octets_from_client{user="hello"} 43403353896 (40.42 GB)
telemt_user_octets_to_client{user="hello"} 834008405024 (776.73 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 123901.5 (34h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4068786
telemt_connections_bad_total 379983
telemt_connections_current 490
telemt_connections_me_current 490
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102496
telemt_upstream_connect_attempt_total 77780
telemt_upstream_connect_success_total 76854
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 77673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10548
telemt_me_reconnect_success_total 3760
telemt_me_reader_eof_total 3743
telemt_me_idle_close_by_peer_total 3743
telemt_me_route_drop_no_conn_total 3650751
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3228639
telemt_me_endpoint_quarantine_total 1003
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 975
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 13186
telemt_desync_full_logged_total 7416
telemt_desync_suppressed_total 5770
telemt_desync_frames_bucket_total{bucket="1_2"} 2994
telemt_desync_frames_bucket_total{bucket="3_10"} 5176
telemt_desync_frames_bucket_total{bucket="gt_10"} 5016
telemt_pool_swap_total 117
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 51615
telemt_me_writer_removed_unexpected_total 3666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6587
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48369
telemt_me_writer_teardown_success_total{mode="normal"} 55321
telemt_me_writer_teardown_noop_total 51616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106937
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.716008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106937
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 3332
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 3243119
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 43623866283 (40.63 GB)
telemt_user_octets_to_client{user="hello"} 808600615377 (753.07 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 198761.5 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16483370
telemt_connections_bad_total 1670138
telemt_connections_current 1226
telemt_connections_me_current 1226
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 401198
telemt_upstream_connect_attempt_total 89563
telemt_upstream_connect_success_total 89456
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1726
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3099
telemt_me_reconnect_success_total 1640
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1592
telemt_me_route_drop_no_conn_total 14070740
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13088698
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1502
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 54410
telemt_desync_full_logged_total 17350
telemt_desync_suppressed_total 37060
telemt_desync_frames_bucket_total{bucket="1_2"} 12123
telemt_desync_frames_bucket_total{bucket="3_10"} 21263
telemt_desync_frames_bucket_total{bucket="gt_10"} 21024
telemt_pool_swap_total 215
telemt_pool_force_close_total 6945
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1077
telemt_me_draining_writers_reap_progress_total 68599
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5765
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61654
telemt_me_writer_teardown_success_total{mode="normal"} 69412
telemt_me_writer_teardown_noop_total 68652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.095453
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1077
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13088667
telemt_user_connections_current{user="hello"} 1226
telemt_user_octets_from_client{user="hello"} 198379802557 (184.76 GB)
telemt_user_octets_to_client{user="hello"} 3536190624451 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 198762.8 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12028905
telemt_connections_bad_total 1268335
telemt_connections_current 891
telemt_connections_me_current 891
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346631
telemt_upstream_connect_attempt_total 103838
telemt_upstream_connect_success_total 102496
telemt_upstream_connect_fail_total 889
telemt_upstream_connect_attempts_per_request{bucket="1"} 103385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43926
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 889
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4560
telemt_me_reconnect_success_total 1958
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1825
telemt_me_route_drop_no_conn_total 4574255
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8904199
telemt_me_endpoint_quarantine_total 1358
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1522
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39163
telemt_desync_full_logged_total 13194
telemt_desync_suppressed_total 25969
telemt_desync_frames_bucket_total{bucket="1_2"} 9697
telemt_desync_frames_bucket_total{bucket="3_10"} 15050
telemt_desync_frames_bucket_total{bucket="gt_10"} 14416
telemt_pool_swap_total 212
telemt_pool_force_close_total 6289
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66685
telemt_me_writer_removed_unexpected_total 1852
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5849
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62547
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60396
telemt_me_writer_teardown_success_total{mode="normal"} 68396
telemt_me_writer_teardown_noop_total 66710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135106
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.573394
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135106
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8841888
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 218603256304 (203.59 GB)
telemt_user_octets_to_client{user="hello"} 3992118198959 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 198726.8 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11170498
telemt_connections_bad_total 1003997
telemt_connections_current 795
telemt_connections_me_current 795
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347617
telemt_upstream_connect_attempt_total 88308
telemt_upstream_connect_success_total 86740
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5833
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 2187
telemt_me_idle_close_by_peer_total 2186
telemt_me_route_drop_no_conn_total 5352284
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8424829
telemt_me_endpoint_quarantine_total 1395
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1480
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38382
telemt_desync_full_logged_total 12731
telemt_desync_suppressed_total 25651
telemt_desync_frames_bucket_total{bucket="1_2"} 9693
telemt_desync_frames_bucket_total{bucket="3_10"} 14704
telemt_desync_frames_bucket_total{bucket="gt_10"} 13985
telemt_pool_swap_total 208
telemt_pool_force_close_total 6189
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 752
telemt_me_draining_writers_reap_progress_total 67265
telemt_me_writer_removed_unexpected_total 2333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62941
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61076
telemt_me_writer_teardown_success_total{mode="normal"} 69534
telemt_me_writer_teardown_noop_total 67336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136870
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.898524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136870
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 752
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2123
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8416718
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 193315129947 (180.04 GB)
telemt_user_octets_to_client{user="hello"} 3494216086353 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69006.9 (19h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11430983
telemt_connections_bad_total 673763
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 294416
telemt_upstream_connect_attempt_total 63543
telemt_upstream_connect_success_total 60162
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 62361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8146
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 25320617
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9474743
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 16815
telemt_desync_full_logged_total 4630
telemt_desync_suppressed_total 12185
telemt_desync_frames_bucket_total{bucket="1_2"} 3224
telemt_desync_frames_bucket_total{bucket="3_10"} 6861
telemt_desync_frames_bucket_total{bucket="gt_10"} 6730
telemt_pool_swap_total 71
telemt_pool_force_close_total 2236
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 506
telemt_me_draining_writers_reap_progress_total 22718
telemt_me_writer_removed_unexpected_total 1298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20482
telemt_me_writer_teardown_success_total{mode="normal"} 23966
telemt_me_writer_teardown_noop_total 22737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46703
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.135428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46703
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 506
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 912
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 9501226
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 88796701210 (82.70 GB)
telemt_user_octets_to_client{user="hello"} 656027905613 (610.97 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 198733.5 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11140525
telemt_connections_bad_total 983898
telemt_connections_current 978
telemt_connections_me_current 978
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245274
telemt_upstream_connect_attempt_total 117108
telemt_upstream_connect_success_total 115912
telemt_upstream_connect_fail_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 116932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1020
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73222
telemt_me_reconnect_success_total 3181
telemt_me_reader_eof_total 2879
telemt_me_idle_close_by_peer_total 2876
telemt_me_route_drop_no_conn_total 5285191
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8769974
telemt_me_endpoint_quarantine_total 1350
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1510
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
telemt_me_writers_active_current 45
telemt_desync_total 46729
telemt_desync_full_logged_total 16045
telemt_desync_suppressed_total 30684
telemt_desync_frames_bucket_total{bucket="1_2"} 9495
telemt_desync_frames_bucket_total{bucket="3_10"} 17902
telemt_desync_frames_bucket_total{bucket="gt_10"} 19332
telemt_pool_swap_total 204
telemt_pool_force_close_total 5911
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71270
telemt_me_writer_removed_unexpected_total 2898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67078
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5162
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65359
telemt_me_writer_teardown_success_total{mode="normal"} 74213
telemt_me_writer_teardown_noop_total 71271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145484
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.330358
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145484
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2682
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8772810
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 196934470377 (183.41 GB)
telemt_user_octets_to_client{user="hello"} 3353913572848 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 135569.8 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11867533
telemt_connections_bad_total 486956
telemt_connections_current 939
telemt_connections_me_current 939
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4802308
telemt_upstream_connect_attempt_total 65949
telemt_upstream_connect_success_total 65476
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 65936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49226
telemt_me_reconnect_success_total 1926
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 4111834
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5700975
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1047
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31992
telemt_desync_full_logged_total 10943
telemt_desync_suppressed_total 21049
telemt_desync_frames_bucket_total{bucket="1_2"} 6391
telemt_desync_frames_bucket_total{bucket="3_10"} 12616
telemt_desync_frames_bucket_total{bucket="gt_10"} 12985
telemt_pool_swap_total 144
telemt_pool_force_close_total 4109
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 51006
telemt_me_writer_removed_unexpected_total 1647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48619
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46897
telemt_me_writer_teardown_success_total{mode="normal"} 52704
telemt_me_writer_teardown_noop_total 51013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103717
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.762903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103717
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1702
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5693003
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 120706259012 (112.42 GB)
telemt_user_octets_to_client{user="hello"} 2216595024214 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 116540.3 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1600509
telemt_connections_bad_total 37034
telemt_connections_current 583
telemt_connections_me_current 583
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32831
telemt_upstream_connect_attempt_total 55159
telemt_upstream_connect_success_total 54987
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 812
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 971
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 535659
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422240
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 966
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
telemt_me_writers_active_current 43
telemt_desync_total 10002
telemt_desync_full_logged_total 2820
telemt_desync_suppressed_total 7182
telemt_desync_frames_bucket_total{bucket="1_2"} 3149
telemt_desync_frames_bucket_total{bucket="3_10"} 3775
telemt_desync_frames_bucket_total{bucket="gt_10"} 3078
telemt_pool_swap_total 126
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 46974
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43800
telemt_me_writer_teardown_success_total{mode="normal"} 47946
telemt_me_writer_teardown_noop_total 46978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94924
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.515420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94924
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 829
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1417921
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 26739229573 (24.90 GB)
telemt_user_octets_to_client{user="hello"} 595009910911 (554.15 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 198738.1 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13439670
telemt_connections_bad_total 1627614
telemt_connections_current 1033
telemt_connections_me_current 1033
telemt_handshake_timeouts_total 392221
telemt_upstream_connect_attempt_total 79810
telemt_upstream_connect_success_total 79453
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 79674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3100
telemt_me_reconnect_success_total 1573
telemt_me_reader_eof_total 1560
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 4498678
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10124267
telemt_me_endpoint_quarantine_total 1457
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1507
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42514
telemt_desync_full_logged_total 13882
telemt_desync_suppressed_total 28632
telemt_desync_frames_bucket_total{bucket="1_2"} 10351
telemt_desync_frames_bucket_total{bucket="3_10"} 15620
telemt_desync_frames_bucket_total{bucket="gt_10"} 16543
telemt_pool_swap_total 220
telemt_pool_force_close_total 5767
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 72234
telemt_me_writer_removed_unexpected_total 1494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68202
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66467
telemt_me_writer_teardown_success_total{mode="normal"} 73784
telemt_me_writer_teardown_noop_total 72236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146020
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.886676
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146020
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1386
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10090879
telemt_user_connections_current{user="hello"} 1033
telemt_user_octets_from_client{user="hello"} 195559515488 (182.13 GB)
telemt_user_octets_to_client{user="hello"} 4489319546572 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 198734.7 (55h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11754958
telemt_connections_bad_total 1378926
telemt_connections_current 892
telemt_connections_me_current 892
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315216
telemt_upstream_connect_attempt_total 107521
telemt_upstream_connect_success_total 106594
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 107313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10861
telemt_me_reconnect_success_total 2686
telemt_me_reader_eof_total 2493
telemt_me_idle_close_by_peer_total 2492
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5666822
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9041965
telemt_me_endpoint_quarantine_total 1630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1513
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
telemt_desync_total 42138
telemt_desync_full_logged_total 13570
telemt_desync_suppressed_total 28568
telemt_desync_frames_bucket_total{bucket="1_2"} 10949
telemt_desync_frames_bucket_total{bucket="3_10"} 15483
telemt_desync_frames_bucket_total{bucket="gt_10"} 15706
telemt_pool_swap_total 210
telemt_pool_force_close_total 5531
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 72490
telemt_me_writer_removed_unexpected_total 2529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6954
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68162
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66959
telemt_me_writer_teardown_success_total{mode="normal"} 75116
telemt_me_writer_teardown_noop_total 72495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147611
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.596674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147611
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9046510
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 158141946416 (147.28 GB)
telemt_user_octets_to_client{user="hello"} 3530893182178 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 118
```