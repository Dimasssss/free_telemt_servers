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

# Server Metrics 2026-03-23 03:58:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 111145.0 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3788482
telemt_connections_bad_total 370080
telemt_connections_current 1161
telemt_connections_me_current 1161
telemt_handshake_timeouts_total 125212
telemt_upstream_connect_attempt_total 41450
telemt_upstream_connect_success_total 41449
telemt_upstream_connect_attempts_per_request{bucket="1"} 41449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1442
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 3023964
telemt_me_route_drop_channel_closed_total 1241
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3087861
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 791
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 871
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
telemt_desync_total 13214
telemt_desync_full_logged_total 4201
telemt_desync_suppressed_total 9013
telemt_desync_frames_bucket_total{bucket="1_2"} 3491
telemt_desync_frames_bucket_total{bucket="3_10"} 4836
telemt_desync_frames_bucket_total{bucket="gt_10"} 4887
telemt_pool_swap_total 123
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 37982
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35553
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34241
telemt_me_writer_teardown_success_total{mode="normal"} 38265
telemt_me_writer_teardown_noop_total 37993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 381.615822
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 575
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3076698
telemt_user_connections_current{user="hello"} 1161
telemt_user_octets_from_client{user="hello"} 43525297256 (40.54 GB)
telemt_user_octets_to_client{user="hello"} 837757958192 (780.22 GB)
telemt_user_unique_ips_current{user="hello"} 522
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 124511.7 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4074841
telemt_connections_bad_total 380399
telemt_connections_current 296
telemt_connections_me_current 296
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102756
telemt_upstream_connect_attempt_total 78131
telemt_upstream_connect_success_total 77199
telemt_upstream_connect_fail_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 78024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 825
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10637
telemt_me_reconnect_success_total 3775
telemt_me_reader_eof_total 3756
telemt_me_idle_close_by_peer_total 3756
telemt_me_route_drop_no_conn_total 3651958
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3233689
telemt_me_endpoint_quarantine_total 1010
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 981
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
telemt_me_writers_active_current 46
telemt_desync_total 13215
telemt_desync_full_logged_total 7435
telemt_desync_suppressed_total 5780
telemt_desync_frames_bucket_total{bucket="1_2"} 3001
telemt_desync_frames_bucket_total{bucket="3_10"} 5188
telemt_desync_frames_bucket_total{bucket="gt_10"} 5026
telemt_pool_swap_total 118
telemt_pool_force_close_total 3269
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 51915
telemt_me_writer_removed_unexpected_total 3679
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6619
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48646
telemt_me_writer_teardown_success_total{mode="normal"} 55634
telemt_me_writer_teardown_noop_total 51916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.728013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3341
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3248163
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 43683306843 (40.68 GB)
telemt_user_octets_to_client{user="hello"} 810633812509 (754.96 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 199371.7 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16496824
telemt_connections_bad_total 1671750
telemt_connections_current 1287
telemt_connections_me_current 1287
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 401722
telemt_upstream_connect_attempt_total 89854
telemt_upstream_connect_success_total 89747
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3102
telemt_me_reconnect_success_total 1643
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1595
telemt_me_route_drop_no_conn_total 14073365
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13099479
telemt_me_endpoint_quarantine_total 1345
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1509
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
telemt_me_writers_active_current 43
telemt_desync_total 54467
telemt_desync_full_logged_total 17367
telemt_desync_suppressed_total 37100
telemt_desync_frames_bucket_total{bucket="1_2"} 12144
telemt_desync_frames_bucket_total{bucket="3_10"} 21290
telemt_desync_frames_bucket_total{bucket="gt_10"} 21033
telemt_pool_swap_total 216
telemt_pool_force_close_total 6969
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1080
telemt_me_draining_writers_reap_progress_total 68870
telemt_me_writer_removed_unexpected_total 1533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5779
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63907
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6499
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61901
telemt_me_writer_teardown_success_total{mode="normal"} 69686
telemt_me_writer_teardown_noop_total 68923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138609
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.229704
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138609
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1080
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1425
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13099435
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 198544226029 (184.91 GB)
telemt_user_octets_to_client{user="hello"} 3540120275407 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 199373.0 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12044158
telemt_connections_bad_total 1271142
telemt_connections_current 804
telemt_connections_me_current 804
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346728
telemt_upstream_connect_attempt_total 104122
telemt_upstream_connect_success_total 102779
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 103669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4563
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1827
telemt_me_idle_close_by_peer_total 1827
telemt_me_route_drop_no_conn_total 4575960
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8912165
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1530
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
telemt_desync_total 39212
telemt_desync_full_logged_total 13205
telemt_desync_suppressed_total 26007
telemt_desync_frames_bucket_total{bucket="1_2"} 9713
telemt_desync_frames_bucket_total{bucket="3_10"} 15073
telemt_desync_frames_bucket_total{bucket="gt_10"} 14426
telemt_pool_swap_total 213
telemt_pool_force_close_total 6312
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66946
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60634
telemt_me_writer_teardown_success_total{mode="normal"} 68659
telemt_me_writer_teardown_noop_total 66971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.578717
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1678
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8849840
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 218659439312 (203.64 GB)
telemt_user_octets_to_client{user="hello"} 3994608590563 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 199337.5 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11183867
telemt_connections_bad_total 1005692
telemt_connections_current 652
telemt_connections_me_current 652
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 348084
telemt_upstream_connect_attempt_total 88619
telemt_upstream_connect_success_total 87049
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42686
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5837
telemt_me_reconnect_success_total 2443
telemt_me_reader_eof_total 2190
telemt_me_idle_close_by_peer_total 2189
telemt_me_route_drop_no_conn_total 5354074
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8431173
telemt_me_endpoint_quarantine_total 1406
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1485
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
telemt_me_writers_active_current 43
telemt_desync_total 38416
telemt_desync_full_logged_total 12741
telemt_desync_suppressed_total 25675
telemt_desync_frames_bucket_total{bucket="1_2"} 9702
telemt_desync_frames_bucket_total{bucket="3_10"} 14718
telemt_desync_frames_bucket_total{bucket="gt_10"} 13996
telemt_pool_swap_total 209
telemt_pool_force_close_total 6209
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 753
telemt_me_draining_writers_reap_progress_total 67548
telemt_me_writer_removed_unexpected_total 2336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63204
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61339
telemt_me_writer_teardown_success_total{mode="normal"} 69820
telemt_me_writer_teardown_noop_total 67619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137439
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.904119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137439
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 753
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2126
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8423054
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 193374970607 (180.09 GB)
telemt_user_octets_to_client{user="hello"} 3496907451697 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69616.4 (19h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11447305
telemt_connections_bad_total 674040
telemt_connections_current 1232
telemt_connections_me_current 1232
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 296449
telemt_upstream_connect_attempt_total 63838
telemt_upstream_connect_success_total 60447
telemt_upstream_connect_fail_total 2202
telemt_upstream_connect_attempts_per_request{bucket="1"} 62649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2202
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8234
telemt_me_reconnect_success_total 1433
telemt_me_reader_eof_total 915
telemt_me_idle_close_by_peer_total 914
telemt_me_route_drop_no_conn_total 25324015
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9487920
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 561
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 16859
telemt_desync_full_logged_total 4647
telemt_desync_suppressed_total 12212
telemt_desync_frames_bucket_total{bucket="1_2"} 3244
telemt_desync_frames_bucket_total{bucket="3_10"} 6877
telemt_desync_frames_bucket_total{bucket="gt_10"} 6738
telemt_pool_swap_total 72
telemt_pool_force_close_total 2259
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 508
telemt_me_draining_writers_reap_progress_total 22965
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2988
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20706
telemt_me_writer_teardown_success_total{mode="normal"} 24225
telemt_me_writer_teardown_noop_total 22984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47209
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.310268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47209
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 508
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 925
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 9514397
telemt_user_connections_current{user="hello"} 1232
telemt_user_octets_from_client{user="hello"} 88927171670 (82.82 GB)
telemt_user_octets_to_client{user="hello"} 661975923817 (616.51 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 199343.0 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11151137
telemt_connections_bad_total 984628
telemt_connections_current 1017
telemt_connections_me_current 1017
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245635
telemt_upstream_connect_attempt_total 117409
telemt_upstream_connect_success_total 116207
telemt_upstream_connect_fail_total 1026
telemt_upstream_connect_attempts_per_request{bucket="1"} 117233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1026
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73342
telemt_me_reconnect_success_total 3194
telemt_me_reader_eof_total 2894
telemt_me_idle_close_by_peer_total 2891
telemt_me_route_drop_no_conn_total 5287216
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8778451
telemt_me_endpoint_quarantine_total 1357
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1515
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
telemt_desync_total 46761
telemt_desync_full_logged_total 16063
telemt_desync_suppressed_total 30698
telemt_desync_frames_bucket_total{bucket="1_2"} 9502
telemt_desync_frames_bucket_total{bucket="3_10"} 17914
telemt_desync_frames_bucket_total{bucket="gt_10"} 19345
telemt_pool_swap_total 205
telemt_pool_force_close_total 5934
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 71528
telemt_me_writer_removed_unexpected_total 2913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65594
telemt_me_writer_teardown_success_total{mode="normal"} 74486
telemt_me_writer_teardown_noop_total 71529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.333711
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 4316
telemt_me_writer_restored_same_endpoint_total 2691
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8781281
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 197106664017 (183.57 GB)
telemt_user_octets_to_client{user="hello"} 3356850235824 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 136179.3 (37h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11881300
telemt_connections_bad_total 486980
telemt_connections_current 779
telemt_connections_me_current 779
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4805409
telemt_upstream_connect_attempt_total 66294
telemt_upstream_connect_success_total 65819
telemt_upstream_connect_fail_total 462
telemt_upstream_connect_attempts_per_request{bucket="1"} 66281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 462
telemt_me_reconnect_attempts_total 49228
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1605
telemt_me_idle_close_by_peer_total 1604
telemt_me_route_drop_no_conn_total 4114191
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5708994
telemt_me_endpoint_quarantine_total 939
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1050
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32057
telemt_desync_full_logged_total 10956
telemt_desync_suppressed_total 21101
telemt_desync_frames_bucket_total{bucket="1_2"} 6407
telemt_desync_frames_bucket_total{bucket="3_10"} 12646
telemt_desync_frames_bucket_total{bucket="gt_10"} 13004
telemt_pool_swap_total 145
telemt_pool_force_close_total 4134
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 51333
telemt_me_writer_removed_unexpected_total 1648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48937
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47199
telemt_me_writer_teardown_success_total{mode="normal"} 53032
telemt_me_writer_teardown_noop_total 51340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104372
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.765334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104372
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1703
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5701017
telemt_user_connections_current{user="hello"} 779
telemt_user_octets_from_client{user="hello"} 120784005552 (112.49 GB)
telemt_user_octets_to_client{user="hello"} 2219341456366 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 336
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 117149.9 (32h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1607314
telemt_connections_bad_total 37088
telemt_connections_current 594
telemt_connections_me_current 594
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32904
telemt_upstream_connect_attempt_total 55431
telemt_upstream_connect_success_total 55257
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 55403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 814
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2412
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 537379
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1428292
telemt_me_endpoint_quarantine_total 993
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 967
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10041
telemt_desync_full_logged_total 2829
telemt_desync_suppressed_total 7212
telemt_desync_frames_bucket_total{bucket="1_2"} 3170
telemt_desync_frames_bucket_total{bucket="3_10"} 3791
telemt_desync_frames_bucket_total{bucket="gt_10"} 3080
telemt_pool_swap_total 127
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 47192
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44605
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44018
telemt_me_writer_teardown_success_total{mode="normal"} 48169
telemt_me_writer_teardown_noop_total 47196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.519393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 834
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1423973
telemt_user_connections_current{user="hello"} 594
telemt_user_octets_from_client{user="hello"} 26810454629 (24.97 GB)
telemt_user_octets_to_client{user="hello"} 596830419567 (555.84 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 199347.8 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13448132
telemt_connections_bad_total 1627632
telemt_connections_current 961
telemt_connections_me_current 961
telemt_handshake_timeouts_total 392738
telemt_upstream_connect_attempt_total 80129
telemt_upstream_connect_success_total 79772
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 79993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3106
telemt_me_reconnect_success_total 1578
telemt_me_reader_eof_total 1565
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 4500401
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10131901
telemt_me_endpoint_quarantine_total 1464
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1514
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
telemt_desync_total 42524
telemt_desync_full_logged_total 13886
telemt_desync_suppressed_total 28638
telemt_desync_frames_bucket_total{bucket="1_2"} 10359
telemt_desync_frames_bucket_total{bucket="3_10"} 15622
telemt_desync_frames_bucket_total{bucket="gt_10"} 16543
telemt_pool_swap_total 221
telemt_pool_force_close_total 5791
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 689
telemt_me_draining_writers_reap_progress_total 72524
telemt_me_writer_removed_unexpected_total 1499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68479
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5617
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66733
telemt_me_writer_teardown_success_total{mode="normal"} 74079
telemt_me_writer_teardown_noop_total 72526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.892591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 689
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1391
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10098503
telemt_user_connections_current{user="hello"} 961
telemt_user_octets_from_client{user="hello"} 195695956988 (182.26 GB)
telemt_user_octets_to_client{user="hello"} 4493855152944 (4.09 TB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 199344.6 (55h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11764628
telemt_connections_bad_total 1379461
telemt_connections_current 874
telemt_connections_me_current 874
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315489
telemt_upstream_connect_attempt_total 107853
telemt_upstream_connect_success_total 106925
telemt_upstream_connect_fail_total 720
telemt_upstream_connect_attempts_per_request{bucket="1"} 107645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 720
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10899
telemt_me_reconnect_success_total 2691
telemt_me_reader_eof_total 2498
telemt_me_idle_close_by_peer_total 2497
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5668859
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9050537
telemt_me_endpoint_quarantine_total 1640
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1518
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
telemt_me_writers_active_current 43
telemt_desync_total 42157
telemt_desync_full_logged_total 13578
telemt_desync_suppressed_total 28579
telemt_desync_frames_bucket_total{bucket="1_2"} 10956
telemt_desync_frames_bucket_total{bucket="3_10"} 15487
telemt_desync_frames_bucket_total{bucket="gt_10"} 15714
telemt_pool_swap_total 211
telemt_pool_force_close_total 5552
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 72800
telemt_me_writer_removed_unexpected_total 2534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68451
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67248
telemt_me_writer_teardown_success_total{mode="normal"} 75431
telemt_me_writer_teardown_noop_total 72805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 145530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 147328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 147867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.601768
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 2149
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 9055073
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 158287776436 (147.42 GB)
telemt_user_octets_to_client{user="hello"} 3536570711950 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 124
```